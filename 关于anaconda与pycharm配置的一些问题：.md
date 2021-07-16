# 关于anaconda与pycharm配置的一些问题：

1、pycharm所有用anaconda配置的环境都在env文件中

2、pycharm新建项目时，可以选择重新配置一个python环境，也可以选择之前已经配置好的环境

<img src="C:\Users\14455\AppData\Roaming\Typora\typora-user-images\image-20210715112244652.png" alt="image-20210715112244652" style="zoom:75%;" />

​	**注意：新建配置环境时要激活环境，才能安装其他第三方包，否则报错**

<img src="C:\Users\14455\AppData\Roaming\Typora\typora-user-images\image-20210715112556912.png" alt="image-20210715112556912" style="zoom:75%;" />

3、在pycharm的终端中可以使用以下指令

​		**conda install 包**：安装包

​		**conda help** : 查看帮助

​		conda list : 查看已经安装的包

​		**conda activate + 环境名 **：激活配置环境和切换新的环境

​		conda create -n 环境名称 python=版本（3.9）：创建一个在python版本（3.9）下新的配置环境