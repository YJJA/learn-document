# Nginx 命令行参数说明
```sh
nginx -h

# 版本号
-v            # show version and exit
-V            # show version and configure options then exit

# 测试配置文件
-t            # test configuration and exit
-T            # test configuration, dump it and exit

-q            # suppress non-error messages during configuration testing

# 发送信号 stop 停止 quit 退出 reload 重新加载
-s signal     # send signal to a master process: stop, quit, reopen, reload

# 设置配置文件地址
-p prefix     # set prefix path (default: /usr/local/nginx/)
-c filename   # set configuration file (default: conf/nginx.conf)
-g directives # set global directives out of configuration file
```
