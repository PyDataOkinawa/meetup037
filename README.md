# PyData.Okinawa Meetup037

## 概要

Kerasで遊ぼう

## これまで

* https://pydataokinawa.connpass.com/event/46026/
* https://pydataokinawa.connpass.com/event/36115/


## 環境構築

Google colaboratoryを利用する(予定)のでローカルでのセッティングは必要ない -> gmailアカウント発行してねと伝える必要がある(TODO)

* https://qiita.com/tomo_makes/items/b3c60b10f7b25a0a5935


## 今回やること

### Kerasとは(15m)

* 歴史
* backend

### チュートリアル(0.8h)

cifar-10使う予定

* 簡単なチュートリアル (用意完了)
* 過学習・未学習 (用意完了)
	* scikit-learnを利用する
	* ハイパーパラメータの調整

### keras tips(1h)

これ1hでできる気がしなくなってきた...  
作るけど、どこか削ろう

* Keras functionの作成(まだ)
	* モデルのデバッグ
	* レイヤー単位で関数を作成し結果を確認する
	* CNNの組み込み
	* CNNの学習結果をvisualize
* Tensorboard(まだ)
	* Callbackで利用
	* 出力する値のカスタマイズ
* 自作レイヤー(まだ)
	* 簡易な処理のレイヤーを自作
	* Denseを自作(重みをもつレイヤーを自作)
* functional api(まだ)
	* 複数の入力モデルを構築する
		* レイヤー・モデル出力のマージ

## 参考URL

* https://qiita.com/kazuyakitahara/items/ef92f93afba5462e9cb3

## 雑メモ

* これぐらいできれば、Kerasの基礎的なことは教えられるのでは
* colaboratoryの使い方とそもそも勉強会で配布できるのか確認する
* ハンズオンで進めようと思うけど、学習とかはcolaboratoryで事前に書いておかないと間に合わない気がする
* Keras作者の本を読み直す