# note
# ls -l 查看软链接实际位置
lrwxrwxrwx. 1 root root 27 Aug 25 09:21 node -> /root/node-v8.11.4/bin/node
lrwxrwxrwx. 1 root root 26 Aug 25 09:21 npm -> /root/node-v8.11.4/bin/npm
# nginx
config /etc/nginx/conf.d
# 防火墙 centos7
sudo systemctl stop firewalld.service && sudo systemctl disable firewalld.service


- [js-xx](https://github.com/leizongmin/js-xss)
- [koa](https://github.com/changeyu/Coding-Guide/blob/master/README.md#koa2系列教程)


#设置环境变量的三种方法 ubantu in win10
###1.1 临时设置
export PATH=/home/yan/share/usr/local/arm/3.4.1/bin:$PATH1

###1.2 当前用户的全局设置
打开~/.bashrc，添加行：export PATH=/home/yan/share/usr/local/arm/3.4.1/bin:$PATH1
使生效：source .bashrc1

###1.3 所有用户的全局设置
$ vim /etc/profile1
在里面加入：export PATH=/home/yan/share/usr/local/arm/3.4.1/bin:$PATH1
使生效 source profile
