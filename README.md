
# China-Telecom-Helper 中国电信助手
中国电信助手 白嫖年入保底256+话费

频道:https://t.me/ChinaTelecomHelper

每月金豆领取(lv6,1000金豆),每日签到(随机金豆),每日喂食宠物.每日登录奖励领取(5金豆),查看我的云盘(10金豆),翻牌 (10金豆),查看我的订单 (5金豆),打开消息 (100金豆),当日分享 (50金豆),浏览生活频道 (5金豆),查看我的金豆 (5金豆),关注直播 (5金豆),观看直播15s (5金豆),打开消息 (100金豆),答问卷 (100金豆),支付宝小程序任务

![image](https://user-images.githubusercontent.com/19371836/219005361-cc37d88c-83f3-4317-876e-9c9d65e9e806.png)



免费使用,禁止买卖,仅限用于学习和研究目的；不得用于商业或者非法用途，否则，一切后果请用户自负。您必须在下载后的24个小时之内，从您的电脑中彻底删除上述内容。

## 前言


活动规则请自行至[wiki](https://github.com/insoxin/China-Telecom-Helper/wiki)查看

感谢法学专业大佬提醒,金豆自动兑换话费模块可能涉及盈利,已移除.可自行手动兑换

金豆每月固定可兑换17元 17*12=204

每签到7天可以200金豆兑换1元话费 365÷7=52.14

再加上不定时活动

年入保底256+


## 配置运行
进入网页https://github.com/insoxin/China-Telecom-Helper/releases
下载适合自己系统的版本


### 以Linux系统, 电信助手版本1.0.11为例

1.打开终端，使用以下命令行下载该文件：
```
wget https://github.com/insoxin/China-Telecom-Helper/releases/download/1.0.11/China-Telecom-Helper_linux_amd64.tar.gz

```
2.下载完成后，使用以下命令行解压该文件：

```
tar -xzvf China-Telecom-Helper_linux_amd64.tar.gz

```
3.解压完成后，进入解压后的目录，使用以下命令行赋予目录及其内部文件和子目录最高权限：
```
chmod -R 777 China-Telecom-Helper_linux_amd64

```

4.进入解压后的目录，使用以下命令行执行China-Telecom-Helper_linux_amd64二进制文件：
```
cd China-Telecom-Helper_linux_amd64

./China-Telecom-Helper_linux_amd64
```

如果您使用的是Ubuntu或其他基于Debian的Linux发行版，并且在运行时遇到缺少某些依赖项的问题，请使用以下命令安装它们：

```
sudo apt-get update

sudo apt-get install libc6-dev libncurses5-dev libstdc++6
```



### 1.验证码登录

验证码获取

公测地址:https://api.isoyu.com/10000/user/send/


![image](https://user-images.githubusercontent.com/19371836/217848074-11a64ba4-ef49-40ba-9524-481f87bc9ad0.png)

免密预授权唯一IDsign获取

![image](https://user-images.githubusercontent.com/19371836/217848451-dc82e619-8527-4ee1-a476-ba1ba87108c7.png)



~~后端今晚已写好,教程和前端完善中...请等待.预计最低一周.比较忙.~~

实在没时间搞,先这样,服务器5月到期,服务器涨价了5倍,大概率不续费

#### 短信登录注意事项:
 
1.短信登录会顶掉客户端,登录IP为北京地区,如下图
![C05E6052-7F44-4E2B-8B64-BDF21D7DF6C5](https://user-images.githubusercontent.com/19371836/223899248-7f39040e-57d0-42ac-89c5-2edeb25a3529.jpeg)


2.经群友反馈,**五分钟内有两人同时接码就会错乱,也就是说,模拟的客户端限制同时一人使用**.请在低峰期使用或自行抓包. 

### 2.自行抓包,填入 

因电信app加强了反抓包,对部分人抓包难度增加,1.0.8版本后逐渐减少抓包依赖


1.0.8版本后,只需填写phone和sign两个参数.其他参数自动获取.如果你想自定义任务依旧可以填写相关参数.

注:sign值在请求头部.


抓包教程:[一些数据值的抓包教程](https://github.com/insoxin/China-Telecom-Helper/wiki/%E4%B8%80%E4%BA%9B%E6%95%B0%E6%8D%AE%E5%80%BC%E7%9A%84%E6%8A%93%E5%8C%85%E6%95%99%E7%A8%8B)

### 定时执行

特别注意:电信官方服务器经常抽风,导致不成功所以让他每八小时执行一下,一天三次.显示空白是服务器抽风,显示聚合任务接口成功才是请求成功了

Linux 可使用 Crontab 设置定时任务

以下是在目录/root/China-Telecom-Helper_linux_amd64/下执行China-Telecom-Helper_linux_amd64二进制文件，并且每天执行三次的例子,它将在每天的0、8和16时执行,请修改适合自己的时间和目录

```

0 0,8,16 * * * cd /root/China-Telecom-Helper_linux_amd64/ && ./China-Telecom-Helper_linux_amd64

```


windows可使用 系统任务计划程序 设置定时任务



## 其他补充

systime默认即可,也可更换国内cdn,


alipay 为支付宝电信小程序cookie

```
cloudflare 全球cdn加速  

https://cloudflare.api.isoyu.com/time/SysTime/?appCode=B586A14C4EC466D33682F8626CCB3794&auturl=api.isoyu.com&num=13

国内 cdn加速

https://api.isoyu.com/time/SysTime/?appCode=B586A14C4EC466D33682F8626CCB3794&auturl=api.isoyu.com&num=13
```

## 运行截图

![image.png](https://pic.rmb.bdstatic.com/bjh/7367f58ef56656fac3c1ed462e658bb9.png)


## 结束

问题反馈:https://github.com/insoxin/China-Telecom-Helper/issues

觉得好用可以给我下面项目点点star, ~~打赏就不必了~~.不盈利.如果你发现有什么签到奖励蛮好的,可以留言,无偿定制


需要打赏了,用于支付服务器费用.

![image.png](https://raw.githubusercontent.com/insoxin/API/master/Sponsor.jpg)



## Stargazers over time

[![Stargazers over time](https://starchart.cc/insoxin/China-Telecom-Helper.svg)](https://starchart.cc/insoxin/China-Telecom-Helper)

