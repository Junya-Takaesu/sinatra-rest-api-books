チュートリアルの記事
https://x-team.com/blog/how-to-create-a-ruby-api-with-sinatra/

アプリの起動
```
bundle exec ruby server.rb
```

※mongod を実行してあること

mongod の起動
```
mongod
```

* mongodb のインストール (wsl2)
    * https://dev.to/seanwelshbrown/installing-mongodb-on-windows-subsystem-for-linux-wsl-2-19m9
* 公式のドキュメントにある ubuntu へのインストール方法をやっても失敗するので注意
    * https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/
    * wsl2 は systemd を使っていないため