# xyz.github.io
site

安裝伪装站点，伪站点路径/home/sldgrbk/xyz

#apt install wget zip unzip

#wget https://github.com/sldgrbk/xyz.github.io/archive/master.zip

#unzip master.zip

#mkdir -p /home/sldgrbk/xyz

#cp -rf xyz.github.io-master/* /home/sldgrbk/xyz




二、启动方式
启动 V2ray：systemctl start v2ray

停止 V2ray：systemctl stop v2ray

状态查询 V2ray：systemctl status v2ray

重启 V2ray 服务：systemctl restart v2ray

启动 Nginx：systemctl start nginx

停止 Nginx：systemctl stop nginx

状态查询 Nginx：systemctl status nginx

重启 Nginx 服务：systemctl restart nginx


三、相关目录
Web 目录：/home/wwwroot/3DCEList

V2ray 服务端配置：/etc/v2ray/config.json

V2ray 客户端配置: ~/v2ray_info.txt

Nginx 目录： /etc/nginx

证书文件: /data/v2ray.key 和 /data/v2ray.crt
