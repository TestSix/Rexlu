#adb
1 使用genymotion安装一个应用(QQlist和淘宝)
1>	查看device状态:

 
2>	把本地的.apk文件上传的device上
 

碰到的问题
 
解决办法
 
NOTE：adb remount的意思是重新挂载系统分区，试系统分区重新可写

3>	安装
遇到的问题
 
解决办法
 
 
NOTE:qq的apk有问题,重新安装淘宝apk成功

2 查看应用的pack name
cd /data/data 
 

3 使用pull和push命令
1>	push上面已经用过
2>	pull命令
 

ddms
1 查看应用的package name
1>	tool\ddms.bat,双击ddms.bat
2>	左上角可以查到packname
 

2 查看某场景的内存增加以及峰值
 
3 增加一个过滤的条件来查看log
 
 

Hierarchyviewer
1 查看应用的结构图
1>	打开tools，双击hierarchyviewer.bat
2>	在界面上选择高亮一行(高亮一行表示当前显示的应用)，并点击<Load view hierarchy>
 
 

2看应用的控件的绘制性能
1>	在tree view视图中选中一个控件，点击<profile note>,可看到view的绘制性能，三个点依次代表创建，绘制，渲染
 



移动无线测试第一节课作业
adb
1 使用genymotion安装一个应用(QQlist和淘宝)
1>	查看device状态:
 
2>	把本地的.apk文件上传的device上
 

碰到的问题
 
解决办法
 
NOTE：adb remount的意思是重新挂载系统分区，试系统分区重新可写

3>	安装
遇到的问题
 
解决办法
 
 
NOTE:qq的apk有问题,重新安装淘宝apk成功

2 查看应用的pack name
cd /data/data 
 

3 使用pull和push命令
1>	push上面已经用过
2>	pull命令
 

ddms
1 查看应用的package name
1>	tool\ddms.bat,双击ddms.bat
2>	左上角可以查到packname
 

2 查看某场景的内存增加以及峰值
 
3 增加一个过滤的条件来查看log
 
 

Hierarchyviewer
1 查看应用的结构图
1>	打开tools，双击hierarchyviewer.bat
2>	在界面上选择高亮一行(高亮一行表示当前显示的应用)，并点击<Load view hierarchy>
 
 

2看应用的控件的绘制性能
1>	在tree view视图中选中一个控件，点击<profile note>,可看到view的绘制性能，三个点依次代表创建，绘制，渲染
 




