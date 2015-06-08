Go Answer
====================

网页版本的答题王，通过Websocket通讯。

安装：
--------------------
    go get github.com/vckai/GoAnswer

说明
--------------------
数据是存在Mongodb，可能使用redis会比较好，但是之前用mongodb比较少，也算是一种学习吧。

安装好之后，通过http://127.0.0.1:9999/addExam 添加题库，这个属于比较简单地添加。

![图1](http://vckai.com/static/up/image/20150606/1433769112.png)

![图2](http://vckai.com/static/up/image/20150606/1433769230.png)

TODO
====================
* 增加TCP协议支持
* 增加用户游戏信息

