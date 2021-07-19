# HeytapTask
欢太商城自动签到脚本


## 已实现功能

* [x] 每日签到
* [x] 每日浏览商品任务
* [x] 每日分享商品任务
* [x] 每日点推送任务
* [x] 可选 钉钉通知、Tg通知、pushplus推送加、企业微信、Bark通知、IFTTT通知 功能

## 使用方式
> 本项目使用 python3 实现
#### 1、下载本项目 左上 CODE - Download ZIP 或 [点此下载](https://github.com/hwkxk/HeytapTask/archive/refs/heads/main.zip)
#### 2、解压后用文本编辑器 打开`config.ini`按注释说明进行填写
#### 3、需要安装的依赖
```
pip install requests 
```
#### 4、执行方法 命令行or终端 转到程序源码目录下 执行
```bash
 python main.py
```

#### 注意：不要fork后将个人信息填写到自己仓库`config.ini`文件中，请下载到本地编辑，以免隐私泄露。
#### cookies 和 User-Agent 信息请自行在手机登录 `欢太商城` APP后使用HttpCanary等抓包工具获取！(具体抓包方式请百度/Google)

## 申明

* 本项目仅用于学习研究，禁止任何人用于商业用途，本人不保证其合法性，准确性，完整性和有效性
* 本人无法100%保证使用本项目之后不会造成账号异常问题，请根据情况自行判断再下载执行！否则请勿下载运行！
* 如果任何单位或个人认为该项目的脚本可能涉及侵犯其权利，则应及时通知并提供相关证明，我将在收到认证文件后删除相关脚本.

## 参考及引用

* [srcrs/UnicomTask](https://github.com/srcrs/UnicomTask)，参考了此项目的结构及推送notify.py代码的引用
