# docker-develop-infra-base

開発用Dockerインフラです。
データベース、phpmyadmin、MailHogが入っています。

# 起動方法

composer docker:up

# 終了方法

composer docker:down

＃ アプリケーション

database(MariaDB)Port 3306
id: user password: password defaultDatabase: database
phpmyadmin http://localhost:3088
MailHog アプリケーション http://localhost:8025/
MailHog SMTP 1025