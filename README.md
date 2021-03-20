# Introduction
複数のwordpressを移行する際に作成しました。  
複数のwordpressを別々のコンテナで作成し、nginxコンテナによってドメイン名で振り分けを行っています。

個人的に使用する目的で作成したものなので、使用する際は自己責任でお願い致します。

# Useage
このリポジトリをクローンした後proxy_setting/default.conf内の\<site_url>を変更していただき、'docker-compose up -d'を実行していただくとコンテナの構築が行われます。
