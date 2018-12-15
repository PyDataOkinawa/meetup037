# PyData.Okinawa Meetup037

## 概要

Kerasで遊ぼう

## これまで

* https://pydataokinawa.connpass.com/event/46026/
* https://pydataokinawa.connpass.com/event/36115/


## 環境構築

Google colaboratoryを利用する(予定)のでローカルでのセッティングは必要ない -> gmailアカウント発行が必要

* https://qiita.com/tomo_makes/items/b3c60b10f7b25a0a5935


## 今回やること

### Kerasとは(15m)

* 歴史
* backend

### チュートリアル(0.8h)

cifar-10使う予定

* 簡単なチュートリアル
* 過学習・未学習
	* scikit-learnを利用する
	* ハイパーパラメータの調整

### keras tips(1h)


* Keras functionの作成
	* モデルのデバッグ
	* レイヤー単位で関数を作成し結果を確認する
	* CNNの組み込み
	* CNNの学習結果をvisualize
* Tensorboard
	* Callbackで利用
	* 出力する値のカスタマイズ
* 自作レイヤー(未完成)
	* 簡易な処理のレイヤーを自作
	* Denseを自作(重みをもつレイヤーを自作)
* functional api
	* 複数の入力モデルを構築する
		* レイヤー・モデル出力のマージ