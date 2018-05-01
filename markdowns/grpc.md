### 単一のソースから各言語用のソースを生成する



### なぜか
* バージョンが揃ってないことで消耗しないため
  * あー ERD 変えたけど SQL 更新してないわ
  * あー API 変えたけどアプリ変えるの忘れてたわ
  * あー API 仕様書がいつのまにか廃墟だわ
  * あーつらいわー



### いいものを速くつくれる
* バージョンが揃ってないことで消耗しない
* Repository tool が活躍中



### まだ生成できるものはある
* API のリクエスト／レスポンス
  * ex: (iOS) APIKit.Request/Response



### そこで gRPC
* Google 製のフレームワーク
* 単一の DSL ファイルから各言語用のリクエスト／レスポンス／APIのインターフェイスのコードを生成できる
* [ishkawa](https://blog.ishkawa.org/2018/02/07/1518029093/)



### gRPC について kwsk
TODO: ここで適当にスライドを見てもらう



### Demo



### 刺激が強すぎるところ
* 覚えることが多い
  * .proto の記法
  * protoc の使い方 etc
* Nullability さよなら
* Rest さよなら、json さよなら
* Rails その他 web framework サヨナラ
* (https://github.com/grpc-ecosystem)[ecosystem] の充実度的に Golang 有利



（ここで gRPC 使えないよね的な意見をいただく）



### 各社の反応
* mercari
* abema



### gRPC、適当なマイクロサービスあたりから採用してみませんか
