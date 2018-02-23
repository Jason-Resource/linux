```
快速到达历史任务

history

!1888  (!任务ID)
```

```
使用 文件内容
mysql -uroot -p'cat /dara/passwd.txt'
```

```
查看文件大小
du -sh lumen.log
```

```
查看/搜索文件
cat lumen.log |grep '错误'|more
cat lumen.log|wc -l
cat lumen.log |head
cat lumen.log |grep '2018-02-06'|grep '错误' >>/tmp/123.txt
```

```
计算 文件相关数据
wc log.txt -l  统计行数
wc log.txt -c  统计Bytes数
wc log.txt -w  统计字数
```


```
 1032  cat lumen.log |grep '接收到用户关注推送'
 1033  cat lumen.log |grep '2018-02-06'|grep '日志错误'
 1034  cat lumen.log |grep '2018-02-06'|more
 1035  cat lumen.log |grep '2018-02-06'|grep '错误'
 1036  cat lumen.log |grep '2018-02-06'|grep '接收到用户关注推送'
 1037  cat lumen.log |grep '2018-02-06'|grep '接收到用户关注推送' >>/tmp/123.txt
 1038  wc -l /tmp/123.txt

 1040  cat lumen.log |grep '2018-02-06'|grep '接收到用户关注推送,数据' |wc -l 
 1041  cat lumen.log |grep '2018-02-06'|grep '接收到用户关注推送, 数据' |wc -l 
 1042  cat lumen.log |grep '2018-02-06'|grep '接收到用户关注推送，数据' |wc -l 
 1043  cat lumen.log |grep '2018-02-06'|grep '推送用户关注数据日志成功' |wc -l 
 1045  cat lumen.log |grep '2018-02-06'|grep '推送用户关注数据日志成功' |grep 'cfhzt'|wc -l 
 1046  cat lumen.log |grep '2018-02-06'|grep '推送用户关注数据日志成功' |grep 'cfhgj'|wc -l 

 1050  cat /usr/local/nginx/logs/user.portrait.58ag8.com_access.log|head
 1051  cat /usr/local/nginx/logs/user.portrait.58ag8.com_access.log-20180207 |head
 1052  cat /usr/local/nginx/logs/user.portrait.58ag8.com_access.log-20180207 |grep '06/Feb/2018'|grep '/api/v1/wechat/insert-subscribe'|wc -l 
 1053  cat /usr/local/nginx/logs/user.portrait.58ag8.com_access.log-20180206 |grep '06/Feb/2018'|grep '/api/v1/wechat/insert-subscribe'|wc -l 
 1054  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '取消关注推送'|tail
 1055  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '2018-02-06'|grep '取消关注推送'|tail
 1056  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '2018-02-06'|grep '取消关注推送'|wc -l 
 1057  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '2018-02-06'|grep '接收到用户取消关注推送'|wc -l 
 1058  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '2018-02-06'|grep '接收到用户取消关注推送'|grep 'cfhgj'|wc -l 
 1059  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '2018-02-06'|grep '接收到用户取消关注推送'|wc -l 
 1060  cat /var/wwwroot/market.centre.sscf.com/storage/logs/lumen.log |grep '2018-02-06'|grep '接收到用户关注推送'|wc -l 
```
