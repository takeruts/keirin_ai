# keirin_ai
### Deep Learning を使った競輪の予測 (AI技術勉強のため）
- TensorFlow を使用
- 収束高速化：　He 初期化, Adam
- 過学習対策：　正則化（２次）、ドロップアウト
- 精度向上：　作業中

## ファイルの説明
### Crawler_train
- トレーニング用のデータを取得しCVSファイルに保存する (data folder)
- 2008年8月から2018年8月までのデータを参照
### Cralwer_predict
- 予想用のデータを取得しCSVファイルに保存する (predict folder)
- 2018年9月分
### train_predict.ipynb
- 学習を実行し、予測結果を表示
#### 未完成
##### train.ipynb
- 学習を実行し、モデルを保存する (model folder)
##### predict.ipynb
- 学習済みモデルをロードして予測する（未完成）
