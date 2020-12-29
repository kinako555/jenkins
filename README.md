# jenkinsサーバー
ver 1.0.0
jenkinsをdocker-composeで構築したもの

## 初期起動
はじめに起動する場合は以下を実行する

```bash
# 起動
$ docker-compose up -d
```
以下のアドレスでアクセスできる
http://localhost:18080
外部端末(ローカル)の場合は以下からアクセスする
http://jenkins起動pcのip:18080

## 運用

## 起動・停止

```cmd
# どのコマンドもjenkinsディレクトリで行う
# 起動
$ docker-compose start
# 停止
docker-compose stop
```


### git
- クリティカルな変更を実施するとき以外は、mainブランチを直接変更する