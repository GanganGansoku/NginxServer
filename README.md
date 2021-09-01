# 技術研究対策　成果物その1
## 注意：dockerが入っていることが前提となります
## nginxサーバー起動
- 起動

クローンして以下のコマンドを実行してください。
```
docker-compose up -d --build
```
ブラウザなどで[localhost:80](localhost:80)にアクセスすればindex.htmlの中身が表示されます。

- 停止
```
docker-compose down
```
なおこのサーバーは最後に停止させてください。