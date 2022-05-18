# China-Telecom-Helper 中国电信助手
中国电信助手

每日签到(随机金豆),每日喂食宠物.每日登录奖励领取(5金豆),查看我的云盘(10金豆),翻牌 (10金豆),查看我的订单 (5金豆),打开消息 (100金豆),当日分享 (50金豆),浏览生活频道 (5金豆),查看我的金豆 (5金豆),关注直播 (5金豆),观看直播15s (5金豆),打开消息 (100金豆),答问卷 (100金豆),部分任务需要手动操作完成


![image.png](https://pic.rmb.bdstatic.com/bjh/7367f58ef56656fac3c1ed462e658bb9.png)


免费使用,禁止买卖,仅限用于学习和研究目的；不得用于商业或者非法用途，否则，一切后果请用户自负。您必须在下载后的24个小时之内，从您的电脑中彻底删除上述内容。

## 前言


活动规则请自行至[wiki](https://github.com/insoxin/China-Telecom-Helper/wiki)查看

金豆自动兑换话费模块可能涉及盈利,已移除.可自行手动兑换

金豆每月固定可兑换17元 17*12=204

每签到7天可以200金豆兑换1元话费 365÷7=52.14

再加上不定时活动

年入保底256+



## 配置运行

程序同目录下创建 config.json 文件或者 https://github.com/insoxin/China-Telecom-Helper/blob/main/config.json 下载填写自值

phone,cookie,para等自行抓包获取

抓包教程:[一些数据值的抓包教程](https://github.com/insoxin/China-Telecom-Helper/wiki/%E4%B8%80%E4%BA%9B%E6%95%B0%E6%8D%AE%E5%80%BC%E7%9A%84%E6%8A%93%E5%8C%85%E6%95%99%E7%A8%8B)

systime默认即可,也可更换国内cdn,

```
cloudflare 全球cdn加速  

https://cloudflare.api.isoyu.com/time/SysTime/?appCode=B586A14C4EC466D33682F8626CCB3794&auturl=api.isoyu.com&num=13

国内 cdn加速

https://api.isoyu.com/time/SysTime/?appCode=B586A14C4EC466D33682F8626CCB3794&auturl=api.isoyu.com&num=13
```

### 完整示例

下列文档中示例json 只是示范,要灵活运用.可能存在与新版本不兼容问题,具体请以 https://github.com/insoxin/China-Telecom-Helper/blob/main/config.json 为准

```
{
	"users": [{
			"cookie": "cookie",
			"para": "para",
			"phone": 13800138000,
			"monthlybeans": "monthly beans",
			"Paradise": [{
				"setting": "true"
			}, {
				"Polymerize": "Polymerize"
			}, {
				"Polymerize": "Polymerize"
			}],
			"systime": "https://cloudflare.api.isoyu.com/time/SysTime/?appCode=B586A14C4EC466D33682F8626CCB3794&auturl=api.isoyu.com&num=13",
			"github": "https://github.com/insoxin/China-Telecom-Helper"

		}

	]
}
```
### 试运行
![image.png](https://pic.rmb.bdstatic.com/bjh/b9f518e9d5ebe4671652700106623c78.png)
根据自己系统下载,如若没有,可留言


Linux 
```
wget https://github.com/insoxin/China-Telecom-Helper/releases/download/0.1/China-Telecom-Helper_0.1_linux_amd64
wget https://github.com/insoxin/China-Telecom-Helper/releases/download/0.1/config.json
chmod +x China-Telecom-Helper_0.1_linux_amd64
./China-Telecom-Helper_0.1_linux_amd64
```
config.json 别忘了填写所有参数

### 定时执行

Linux 可使用 Crontab 设置定时任务

windows可使用 系统任务计划程序 设置定时任务


## 运行截图

![image.png](https://pic.rmb.bdstatic.com/bjh/7367f58ef56656fac3c1ed462e658bb9.png)

## 结束

觉得好用可以给我下面项目点点star,打赏就不必了.不盈利.如果你发现有什么签到奖励蛮好的,可以留言,无偿定制

https://github.com/insoxin/api

https://github.com/insoxin/China-Telecom-Helper
