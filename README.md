# yysAuto
阴阳师PC端自动挂业原火和御灵

##更新：

1.改进了鼠标移动函数，不会瞬移，会模范人为缓慢移动

2.加入了挂机时长参数，可以指定挂机时间

3.优化代码
```

```  


##使用方法：

目前没封装成exe,主要懒得写图形界面，有空再完善

1.必须PC客户端，不能模拟器。win10系统清打开设置->系统->显示，将文本缩放调至100%

2.安装python环境，安装源码头文件的所需库（numpy,opencv,QT5,pyautogui等），不会的问度娘

3.修改主函数（108行，没IDE的可用记事本打开）Model。两个参数分别为模式和时间（以秒计算），比如修改改为Model("yulin3",5000)表示刷御灵黑豹，挂机5000秒

4.将游戏窗口左上角拖至屏幕左上角对齐，管理员权限打开cmd(必须)，进入代码所在目录,执行python yyysAuto.py，Crtl+C键停止。

```

```  
##注意事项：

1.cmd输出的第一行分别表示截图次数，点开始无反应次数（3次自动停止），挂机时间（超时自动停止），第二行是截图特征值。

2.由于是截图识别，所以被人拉协作任务会打断，目前正在优化，最好隔断时间检查一下。
