# opencv-face-recognition
使用opencv肝出来了的东西还有很多bug（一个多星期的东西能有多好），有图形界面，可以进行数据库管理。

请使用 python run.py 运行程序。

在人脸识别时检测到编号为1的用户（就是我自己的图片你们可以用我的照片试试应该可以）就会提示进入管理员界面。

更改管理员去看代码，在一个字典里面，应该很容易的

进入后，提示输入管理员编号和密码的两行

编号输入1

密码wwgb1314

然后输入yes，确定登录

使用anaconda初始环境所需要的额外库：opencv

命令：conda install opencv

本程序在添加新人、登录管理员界面等场景，

（本来写了微信推送发现没卵用直接忽视这条）

会通过Server酱提供的API向绑定的微信发送通知。大家可以去Server酱申请自己的API，并替换FaceTool.py中133行api变量的值以向自己的微信发送通知。或改动代码删除此功能（自己懒得改了^）。