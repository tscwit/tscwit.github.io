# docsify基本使用

## 侧边栏

​	侧边栏为sidebar,如果想要使用侧边栏,那么先创建一个_sidebar.md文件,之后在index.html中的windous.$docsify下面添加loadSidebar:true。

## 导航栏

​	导航栏为navbar,如果想要使用导航栏,那么先创建一个_navbar.md文件,之后在index.html中的windous.$docsify中添加loadNavbar = true

## 主页

​	主页是一开始就有的,在设置号主页之后,在主页界面滚轮向下滑动就可以进入到首页。如果,想要将主页独立出来一个页面,那么就在index.html文件中的windous.$docsify中添加onlyCover = true

## 子目录

如果想要侧边栏和导航栏的子目录也有导航,那么就在index.html的windous.$docsify中添加subMaxlevel = 2。这个数字"2"表示显示到侧边栏的多少个层次

## 如何设置导航的层次

​	设置的格式为

```
* [首页](README.md)
```



