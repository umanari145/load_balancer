# ロードバランサーのテスト

## ファイル構成
- proxy バランサー
- docker/web1 Dockerfileとnginxの設定ファイル
- docker/web2 Dockerfileとnginxの設定ファイル
- web1 配下のサーバー1 (index.html)
- web2 配下のサーバー2 (index.html)

# 結果

http://load-balancer.local:8080/ に何度かアクセスし、<br>
webserver1,webserver2が両方表示されていればOK
