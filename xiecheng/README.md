# 携程房价抓取

##### 运行方式
* 启动server.js服务
    * server.js的功能是解析eleven的值
* 运行main.py
    * 根据hotalid和cityid进行抓取
    * 并会生成xiecheng.html文件,用firefox打开，选择unicode编码，和main函数请求的地址的价格进行对比
    
### 反爬点 ###

![](https://i.imgur.com/u2n8beV.jpg)

### 效果mp4 ###
*  见项目


##### 已解决的问题
* eleven 值的自动获取
* 房价数据的字体转换
* cookie自动生成的问题
    * _zQdjfing
    * fcerror
    * hashCode重写
