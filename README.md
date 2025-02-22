# keirin_ai
## Deep Learning を使った競輪の予測
- TensorFlow, Keras を使用
- 収束：　He 初期化, Adam
- 過学習対策：　正則化（２次）、ドロップアウト
- 予測精度: 作業中（いまのところ、実用的な結果を得られない)

### ログ

### ファイルの説明
#### Crawler_train
- トレーニング用のデータを取得しCVSファイルに保存する (data folder)
- 2008年8月から2018年8月までのデータを参照 (146,536レース分)
#### Cralwer_predict
- 予想用のデータを取得しCSVファイルに保存する (predict folder)
- 2018年9月分
#### train_predict.ipynb
- 学習を実行し、予測結果を表示
##### 未完成
###### train.ipynb
- 学習を実行し、モデルを保存する (model folder)
###### predict.ipynb
- 学習済みモデルをロードして予測する（未完成）

### 学習データ
-  Kドリームスを参照　https://keirin.kdreams.jp/

| 地域 | 競輪場 |
|:---|:---|
| 北日本 | 函館競輪 青森競輪 いわき平競輪 |
| 関東 | 弥彦競輪 前橋競輪 取手競輪 宇都宮競輪 大宮競輪 西武園競輪 京王閣競輪 立川競輪 |
| 南関東 | 松戸競輪 千葉競輪 川崎競輪 平塚競輪 小田原競輪 伊東競輪 静岡競輪 |
| 中部 | 名古屋競輪 岐阜競輪 大垣競輪 豊橋競輪 富山競輪 松阪競輪 四日市競輪 |
| 近畿 | 福井競輪 奈良競輪 向日町競輪 和歌山競輪 岸和田競輪 |
| 中国 | 玉野競輪 広島競輪 防府競輪 |
| 四国 | 高松競輪 小松島競輪 高知競輪 松山競輪 |
| 九州 | 小倉競輪 久留米競輪 武雄競輪 佐世保競輪 別府競輪 熊本競輪 |
