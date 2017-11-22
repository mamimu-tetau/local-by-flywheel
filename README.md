## MacでBrowserSyncと一緒にもにょもにょする
##### flywheelで作ったURL（hoge.local）をホストファイルに登録
flywheelが自動で作ったドメインとは別に登録
```
127.0.0.1 localhost
192.168.95.100 hoge.local
```
これだけだとlocalhost:3000にアクセスした場合読み込み激重
```
::1 localhost
fe80::1%lo0 localhost
::ffff:c0a8:5f64 hoge.local
```
ipv6用のアドレスも追加すると幸せ

git通知テスト
git通知テスト
