# 自述
24元阿里云香港轻量服务器在每天凌晨0:00放货，一般10秒内库存会被抢空。这个脚本是一个自动化工具，能够帮助你轻松地抢到这些抢手的阿里云24元香港轻量服务器。通过预先设定好的参数和算法，它可以在服务器上线的瞬间自动执行购买操作，大大提高了成功抢购的机会。无需手动刷新页面或者不断尝试，这个脚本可以让你在竞争激烈的情况下轻松抢到心仪的服务器。


# 使用
开始前请准备好python环境，
```
pip install alibabacloud_swas_open20200601 alibabacloud_tea_openapi alibabacloud_tea_util alibabacloud_tea_console
```
修改sample.py 填写以下两个字段：
access_key_id=''
access_key_secret=''

，可以使用宝塔的定时计划任务0:00时运行这个脚本。
```
/usr/bin/python3 /路径/hongkong.py
```

注意，在脚本运行前请确认你的阿里云账号余额有24元的资金，否则订单会处理失败。



阿里云轻量服务接入点 地区api查询

https://help.aliyun.com/zh/simple-application-server/developer-reference/api-swas-open-2020-06-01-endpoint?spm=a2c4g.11174283.0.i3
