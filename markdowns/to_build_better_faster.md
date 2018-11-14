### 良いものを早く仕上げる



### 良いものってなんですか
* バグがない
* メンテナンスしやすい



### 良いものってなんですか
* バグがない



### UV のバグの減らし方
* 青柳さんコードレビュー
	（バグりやすい構造をある程度減らす）
* 個人の腕力
* 手動テスト
* 自社事業ではたまに自動テスト



### 2017年私達の組織は大きくなりました
エンジニアの数 1.5倍？
今後もこの傾向は続きそう



### 大きくなりつつ多様化しています
* 残念ながら Mac が嫌いな方
* js ならどんな難をも受け入れるすごい方
* 変な言葉を定着させる方



### 技術レベルバラバラ
UV はどっちかというとポテンシャル採用



### （再掲）UV のバグの減らし方
* 青柳さんコードレビュー
	（バグりやすい構造をある程度減らす）
* 個人の腕力
* 腕力による手動テスト
* 自社事業ではたまに自動テスト



### （再掲）UV のバグの減らし方
* 青柳さんコードレビュー
	（バグりやすい構造をある程度減らす）
* 個人の腕力
* 腕力による手動テスト
* 自社事業ではたまに自動テスト
**持続しにくくなってきている**



### バグがよく出る／バグが出ないように修正することが難しいプロジェクトたち
* Beluga 2
* Beluga Apps (iOS)
* チラシプラス (iOS)
他？



### 最近の UV のバグを減らす取り組み
* Beluga 3
    * SystemTestCase
    * ESLint
    * マージリクエスト
* PP
    * リファクタ会



### バグの減らし方
* まずバグをみつける
* [このスライド](https://speakerdeck.com/orgachem/baguwodofalseyounijian-tukeruka)によくまとまっている



### リリース前／アップデート前のバグの減らし方
* きれいな設計／コード
* 単体／結合テスト



### リリース後出るバグは分かり次第潰す
* エラーのロギング
    * 見やすくエラーを通知しよう／残そう
    * モバイルアプリだと Crashlytics に遺言を吐くことから
    * Web だと Slack やメールに BigQuery にためたログを見やすく吐き出す？


### 単体テストに対する僕の意見
* 元が取れるかわからない
* やりたい


### 良いものってなんですか
* バグがない
* **メンテナンスしやすい**



### メンテナンスのしやすさを持続させたい
* 難題
* リファクタ会が行われるということは開発中にメンテしやすさがすでに損なわれているということ
* 個人の腕力にかかっていそう



### UV の過去の取り組み
* 読書 (コードコンプリート) で実力底上げ



### 理想
* 違和感を覚えたらリファクタリング

### 現実
* そんな暇ないです
* デグレ怖いですし
[https://speakerdeck.com/takanamito/dokiyumentototesutofalsenaipuroziekutowoyin-kiji-gu](https://speakerdeck.com/takanamito/dokiyumentototesutofalsenaipuroziekutowoyin-kiji-gu)



### どうにか楽にメンテナンス性を保ちたい
やっぱりはっきりいって難題



### 負債返済日？
[ぐぐった](https://www.google.co.jp/search?q=%E9%96%8B%E7%99%BA+%E8%B2%A0%E5%82%B5%E8%BF%94%E6%B8%88%E6%97%A5&oq=%E9%96%8B%E7%99%BA%E3%80%80%E8%B2%A0%E5%82%B5%E8%BF%94%E6%B8%88%E6%97%A5&aqs=chrome..69i57.6888j0j7&sourceid=chrome&ie=UTF-8)



### 行ってまいりました
[SRE-SET Automation Night](https://www.google.co.jp/search?q=qa+set+sre&oq=qa+set+sre&aqs=chrome..69i57.3843j0j9&sourceid=chrome&ie=UTF-8)



### 感想
メンテナブルなコードを書く、ことはすでに行われた上で
* ログやテスト結果等の全保存して見やすく表示
* デプロイ簡略化
の話が多かった。
みんなどうにか自動化して楽にしようとがんばっている感じ
とはいえ、その規模と組織の規模には相関があるように思う



### つづきは年末のブレストで
投げっぱなしでごめんなさい
おしまい