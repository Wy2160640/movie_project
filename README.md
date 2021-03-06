# flask构建弹幕微电影系列源码+教程(已上线)

[![Build Status](https://travis-ci.org/mtianyan/hexoBlog-Github.svg?branch=master)](https://travis-ci.org/mtianyan/hexoBlog-Github)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

>flask构建弹幕微电影系列源码+教程:

简书持续更新教程地址: https://www.jianshu.com/nb/15899039

静态前端源码仓库: https://github.com/mtianyan/movie_project_html

>第四章的小博客项目源码地址: https://github.com/mtianyan/FlaskGetStarted

## 原版课程: [原版视频课程地址:](https://coding.imooc.com/learn/list/124.html)


## 项目下载及运行:

- 基础运行环境安装:

```
git clone https://github.com/mtianyan/movie_project
cd movie_project
pipenv shell
pip install -r requirement.txt
# 新建一个movie数据库(自行新建) ; 修改config目录下的base_config中数据库用户密码，管理员用户密码
python generate_tables.py
python manage.py runserver
```

打开网址: http://127.0.0.1:5000/ 访问首页; http://127.0.0.1:5000/admin 访问后台。

## 求打赏鼓励

很高兴我写的文章（或我的项目代码）对你有帮助，请我吃包辣条吧！

微信打赏:

![mark](http://myphoto.mtianyan.cn/blog/180302/i52eHgilfD.png?imageslim)

支付宝打赏:

![mark](http://myphoto.mtianyan.cn/blog/180302/gDlBGemI60.jpg?imageslim)

## 关于我

[简书](https://www.jianshu.com/u/db9a7a0daa1f) && [mtianyan's blog](http://blog.mtianyan.cn/)

有趣的Python群：619417153

欢迎关注简书，star项目！谢谢！你的关注支持是我继续分享前进的动力。
