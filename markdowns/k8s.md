### `K8s`



### Kubernetes へ捧げる言葉    
プロセスを再起動するために午前 3 時に起きねばならなかったシステム管理者、   
あるいはノート PC で動いたのと同じように動かないのを確認するためだけに本番にコードをプッシュした開発者、     
あるいはホスト名が更新されていなかったせいで本番システムに向けて負荷テストをかけてしまったシステムアーキテクト。   
Kubernetes はそんな人たちから感謝されるでしょう。   



### Beluga 2.0 証明書更新のやり方
```
# rds
psql -p 5432 -h $HOST -W -U $USER -f ./update_iphone_cert_prod.sql beluga
# deploy
cd ~/Development/beluga_setup/git/reserve
deploy/vps0032.sh
# vps0032
ssh uniquevision@$VPS32
# daemon 再起動
sudo systemctl restart reserve_daemon.service
# 動作確認
```



### Kubernetes へ捧げる言葉(続)     
Kubernetes の目的をひとことで言えば、分散システムを構築し、デプロイし、メンテナンスするタスクを根本的にシンプルにすることです。    
Kubernetes は、信頼性の高いシステムを構築する長い経験を元にして、その経験が大喜びとまではいかないまでも楽しいものになるようデザインされてきました。   

※ オライリー本より



### 読み方、書き方  
クーベネティス/クーベルネイテス、よく K8s と略記される   

※ wikipedia より



### `K8s`   
* オープンソースのコンテナオーケストレーションシステム
* 元々 Google が設計した
* Beluga 3.0 で使ってみている



### コンテナオーケストレーションシステム？  
docker-compose があるじゃまいか



### docker-compose と Kubernetes のちがい    
* docker-compose    
used for starting containers on the same host.  
* Kubernetes
for running and connecting containers on multiple hosts.    

https://stackoverflow.com/questions/47536536/whats-the-difference-between-docker-compose-and-kubernetes



### 触った感想
* 用語、登場人物が多い
* ドキュメントの量多い。全く読み切れていない
* でもとりあえず動かすところまでなら、なんとか到達できる



### とりあえず動かすところまで到達していただきます



### `K8s` 入門ハンズオン



### 本日のプログラム
1. nginx コンテナを動かしてみよう
1. docker-compose で nginx コンテナを動かしてみよう
1. K8s で nginx コンテナを動かしてみよう
