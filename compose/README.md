1. 在当前文件夹中新建 `mount` 文件夹。

2. 运行 `docker-compose up -d` 安装 PicHome 。

3. PicHome 站点为 [http://\<ip-or-hostname\>:8095/](http://\<ip-or-hostname\>:8095/) ，MariaDB 端口不对宿主机开放。

4. 打开站点进入安装向导，需要将 `填写数据库信息 > 数据库服务器` 改为 `db` 。

5. 推荐将图库放在宿主机 `./mount/site/library` 文件夹中。

6. 这里有一些实用的 Docker Compose 脚本工具 https://github.com/zzc-tongji/tool/tree/main/docker-container/.common 。

