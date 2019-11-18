# 前提条件

* このシェルを実行するマシンに jq がインストールされていること

# 使い方
* 踏み台サーバの セキュリティグループに、自端末からのSSHアクセスのみを許可するルールを設定

* Sg スタックのパラメータに、MyIpAddress キーを用意し、その値に自端末のグローバルIPをセットしている

* 本シェルを実行すると、自端末のグローバルIPを取得して、それを上記パラメータにセットし、踏み台サーバのセキュリティグループが更新される