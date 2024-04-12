# 指定使用 mariadb:10.6 映像檔
FROM mariadb:10.6

# 設定環境變量 TZ 的值為 UTC。這個環境變量用於指定時區，這里將其設置為協調世界時（UTC）。
ENV TZ=UTC

# 將位於本地 ./containers/mariadb/my.cnf 路徑下的檔案覆制到鏡像中的 /etc/my.cnf 路徑。這個指令用於將自定義的 mariadb 配置文件覆制到鏡像中，以覆蓋默認的 mariadb 配置。
COPY ./containers/mariadb/my.cnf /etc/mysql/my.cnf