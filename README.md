# study-linux

环境centos7 

检查当前谁在登录：w

检查谁曾经登录过： last

检查历史：history

开机自启动nginx ：systemctl enable nginx.
systemctl start nginx

重启 reboot

开起koa2 服务 pm ./bin/www

删除进程 pm2 delete

开机自启动pm2的koa服务：pm2 save ,pm2 startup centos ,systemctrl enable pm2-root.service

检查自启动服务：systemctl list-dependencies

开启php-fpm service php-fpm start 

检查有关的目录再哪里：whereis [php]

参看进程并筛选：ps -ef | grep [name] 

rm 删除文件

rm -rf 不询问强制删除所有文件

查看服务状态：service [服务] status


