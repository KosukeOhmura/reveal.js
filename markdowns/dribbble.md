### Dribbble iOS アプリを読み解く



### Dribbble とは
* デザイナー版 GitHub 的な感じ
* 世界中で使われているようだ
* https://dribbble.com/
* API が公開されている



### なぜか
* ReactorKit 作者の人が作ったアプリ
* GitHub で全ソースコードが公開されている
* Testable なつくり
* CI / CD と叫んでいる UV だが、ネイティブアプリについては肝心のテスト戦略が無いので手本にしたい



### Beluga 3 でのテスト
* Rails の API の単体テストは簡単
    * 事前条件をセット
    * 動作させる
    * 事後条件を確認



### アプリの単体テストをするのは一筋縄にはいかない
* 事前条件をセット
* 動作させる
* 事後条件を確認    
...なにが？



### Dribbble iOS アプリ
(動画を流す)



### Dribbble iOS アプリ概要
* ReactorKit で Flux を行うアプリのサンプルを ReactorKit 作者本人が作った
* DI を使ってアプリが依存するものを置き換えられるようにしている
* これを真似するところから単体テストをはじめませんか



### ReactorKit 作者から ReactorKit を学ぶ
* https://www.slideshare.net/devxoul/hello-reactorkit



### Let's コードリーディング
https://github.com/devxoul/Drrrible
