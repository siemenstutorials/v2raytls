# v2raytls

````
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/siemenstutorials/v2raytls/master/install.sh" && chmod +x install.sh && bash install.sh


启动方式
启动 V2ray：systemctl start v2ray

停止 V2ray：systemctl stop v2ray

启动 Nginx：systemctl start nginx

停止 Nginx：systemctl stop nginx

相关目录
Web 目录：/home/wwwroot/3DCEList

V2ray 服务端配置：/etc/v2ray/config.json

V2ray 客户端配置: ~/v2ray_info.inf

Nginx 目录： /etc/nginx

证书文件: /data/v2ray.key 和 /data/v2ray.crt
