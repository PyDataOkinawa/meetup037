# PyData.Okinawa Meetup037

## 概要

Kerasで遊ぼう

## これまで

https://pydataokinawa.connpass.com/event/46026/
https://pydataokinawa.connpass.com/event/36115/


## 環境構築

Google colaboratoryを利用する(予定)のでローカルでのセッティングは必要ない

https://qiita.com/tomo_makes/items/b3c60b10f7b25a0a5935


## 今回やること

### Kerasとは(15m)

* 歴史
* backend

### チュートリアル(0.8h)

cifar-10使う予定

* 手法を変えてみて精度を比較してみる
	* 手法
		* 全結合
		* CNN
			* CNN可視化
* 過学習・未学習
	* scikit-learnを利用する
	* ハイパーパラメータの調整

### keras tips(1h)

* Keras functionの作成
	* モデルのデバッグ
	* レイヤー単位で関数を作成し結果を確認する
	* CNNの学習結果をvisualize
* Tensorboard
	* Callbackで利用
	* 出力する値のカスタマイズ
* 自作レイヤー
	* 簡易な処理のレイヤーを自作
	* Denseを自作(重みをもつレイヤーを自作)
* functional api
	* 複数の入力モデルを構築する
		* レイヤー・モデル出力のマージ

## 参考URL

* https://qiita.com/kazuyakitahara/items/ef92f93afba5462e9cb3

## 雑メモ

* これぐらいできれば、Kerasの基礎的なことは教えられるのでは
* colaboratoryの使い方とそもそも勉強会で配布できるのか確認する
* ハンズオンで進めようと思うけど、学習とかはcolaboratoryで事前に書いておかないと間に合わない気がする
* Keras作者の本を読み直す