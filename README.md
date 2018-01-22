IRKitESP8266
=====

IRKit Clone on ESP8266

## これは何

Toshiyuki Kawashima氏の[ESP8266IRKit](https://github.com/toskaw/ESP8266IRKit) をベースに、以下の2点の追加・改変を行ったものです。
* ボタンを追加、長押しで初期化
* 動作状態をLED(WS2818B)で表示

## 基板データ

IRKitESP8266.{brd,sch}がEagleデータです。適当な方法で製造してください。

## ソースコード

上記のToshiyuki Kawashima氏の「作り方（ソースからコンパイルする方法）」の通りに進めます。


## 使い方

基本的に純正IRKitと同じです。スマホのIRKitアプリで初期設定を行ってください。初期パスワードは"0000000000"です。


## 参考にしたもの

* [minlRum](https://github.com/9SQ/minIRum)

* [IRKit](http://getirkit.com/)

* [ESP8266IRKit](https://github.com/toskaw/ESP8266IRKit)

## 直近のToDo
* LED点滅が未実装（輝度半分として実装）なので実装したい

## Author

Junichi Akita (@akita11, akita@ifdl.jp)
