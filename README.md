### local by flywheel

#### MacでBrowserSyncと一緒にもにょもにょする
```
sudo apachectl start
sudo apachectl stop
sudo apachectl restart
```
### flywheelで作ったURL（hoge.local）をホストファイルに登録
flywheelが自動で作ったドメインとは別に登録
```
127.0.0.1 hoge.local
```
これだけだとlocalhost:3000にアクセスした場合読み込み激重
```
::1 hoge.local
```
ipv6用のアドレスも追加すると幸せ

