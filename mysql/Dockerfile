FROM mysql:8.0
#使うDockerイメージ

#ポート
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./mysql/my.cnf /etc/mysql/conf.d/my.cnf

#docker runに実行される
CMD ["mysqld"]
