# 配置

## 下载wampserver 

1. 配置window 下的host 文件，配置一个域名

``` 
 127.0.0.1       zhuoyujie.com
```

2. wamp 下bin/apache/conf/extra/vhost 文件配置一个虚拟域名指向

``` 
# 配置一个zhuoyujie.com 虚拟主机
<VirtualHost *:80>
	ServerName zhuoyujie.com
	DocumentRoot D:/wamp64/www/zhuoyujie.com/public
</VirtualHost>
```
## git 记住密码
 1. 在.git/config 文件中添加如下代码 
 
 ``` 
 [credential]   
     helper = store
 ```
