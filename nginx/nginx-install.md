# Centos 平台安装

## 一、安装依赖库
### Centos平台编译环境使用如下指令
```
yum -y install make gcc-c++ libtool
```

### Nginx 中gzip模块需要 zlib 库，rewrite 模块需要 pcre 库，ssl 功能需要 openssl 库。
```
yum -y install zlib zlib-devel
yum -y install pcre pcre-devel
yum -y install openssl openssl-devel
```

## 二、安装 Nginx
```
#选定源码目录
cd /usr/local/src

#下载 nginx
wget http://nginx.org/download/nginx-1.13.10.tar.gz

#解压
tar zxvf nginx-1.13.10.tar.gz
cd nginx-1.13.10

#编译安装
./configure
make
make install
```
