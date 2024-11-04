# SIGNATS テクノプロ・デザイン社 日本舞踊の画像・動画解析チャレンジ（学生部門・社会人部門）

本コンペティションの社会人/学生部門では、機械学習の手法などを用いて日本舞踊の1シーンから扇子を持っているのか、持っていないのか自動分類するアルゴリズムを構築する．


▼提供データ

・日本舞踊を踊っている人物の画像

・各画像に対応した踊り手が扇子を所持しているか否かのフラグ情報


# 方針
- データ分割
- データオーギュメンテーション
- ReSNet学習（フラグ0,1出力，損失関数CrossEntropy）
- 各サンプルのConfidence値取得
- Curriculum学習　ReSNet
- アンサンブル
  


