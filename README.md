IRKitESP8266
=====

IRKit Clone on ESP8266

## これは何

Toshiyuki Kawashima氏の[ESP8266IRKit](https://github.com/toskaw/ESP8266IRKit) をベースに、以下の2点の追加・改変を行ったものです。
* ボタンを追加、長押しで初期化
* 動作状態をLED(WS2812B)で表示

## 基板データ

IRKitESP8266.{brd,sch}がEagleデータです。適当な方法で製造してください。

※LED電流制限抵抗としてR4とR11の2つがありますが、どちらか一方のみの実装でよいです。流れる電流からして、R11のほうがオススメです（13Ωと書いてありますが、10Ω前後のものでよいはず）。ただこのあたりは要調整で、SwitchScienceのESP-IRではもっと小さな抵抗を使っているようです。10Ωか4.7Ωの0603サイズ（インチ：ミリだと1608）を、R4とR11の両方に実装するくらいでいいかもです（試していないのでLED破損の恐れがありますので要注意）。

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
