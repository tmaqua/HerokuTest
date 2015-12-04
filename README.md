# Welcome to Heroku

## Heroku sign up

https://www.heroku.com  

## Heroku toolbelt

### local

Herokuのページからダウンロードしてインストール

### vagrant

http://qiita.com/super-hot-engineer/items/beec60ce96f093506631
参考に

## Create App

$ heroku コマンドが打てたら大丈夫  
$ heroku login でログイン  

### git 必須

$ git init  
$ git add .  
$ git commit -m "inital commit"  

### Heroku create

$ heroku create APP_NAME  
APP_NAME無くても自動で作ってくれる  

### push
$ git push heroku master  
masterブランチをherokuにpush  

$ heroku open  
かcreateした時にurl吐き出すからそのurlにアクセスして確認  

### その他

#### destroy
$ heroku apps:destroy --app アプリ名 --confirm アプリ名  

