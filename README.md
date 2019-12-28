# Library Management System

### 基于Java和SQL Server 2008开发的一款图书馆管理系统，具备基本的增、改、查、备份与恢复功能  

#### 注意事项
1. 数据库和备份文件在Datebase目录下  
2. setting.txt四行分别对应：ip、端口、数据库登陆用户名、登陆密码  
3. 登陆请使用Manager表中的用户名和密码进行登陆
4. 开发中我觉得比较能解决疑惑的链接都放到了 **解惑的链接.txt** 里了
5. 入口为 **Main.java** 文件

#### 系统功能模块
![系统功能模块](http://7xsy54.com1.z0.glb.clouddn.com/%E7%B3%BB%E7%BB%9F%E5%8A%9F%E8%83%BD.png)

#### 运行效果：
登陆界面：  
![登陆界面](http://7xsy54.com1.z0.glb.clouddn.com/%E7%99%BB%E9%99%86%E7%95%8C%E9%9D%A2.png)  
修改配置：  
![修改配置](http://7xsy54.com1.z0.glb.clouddn.com/%E4%BF%AE%E6%94%B9%E9%85%8D%E7%BD%AE.png)  
添加界面：  
![添加](http://7xsy54.com1.z0.glb.clouddn.com/%E6%B7%BB%E5%8A%A0%E7%95%8C%E9%9D%A2.png)  
修改界面：  
![修改](http://7xsy54.com1.z0.glb.clouddn.com/%E4%BF%AE%E6%94%B9%E7%95%8C%E9%9D%A2.png)  
查询界面：  
![查询](http://7xsy54.com1.z0.glb.clouddn.com/%E6%9F%A5%E8%AF%A2%E7%95%8C%E9%9D%A2.png)  
修改密码：  
![修改密码](http://7xsy54.com1.z0.glb.clouddn.com/%E4%BF%AE%E6%94%B9%E5%AF%86%E7%A0%81.png)  
备份与恢复：  
![备份与恢复](http://7xsy54.com1.z0.glb.clouddn.com/%E6%95%B0%E6%8D%AE%E5%BA%93%E5%A4%87%E4%BB%BD%E4%B8%8E%E6%81%A2%E5%A4%8D.png)  

------- 分割线-----

从中学到了很多，之前制作过一些简单的GUI界面的游戏，比如之前的扫雷，但是还有许多Swing的控件没有学习，包括但不限于
1. JDesktopPane 像桌面一样，可以放置很多JInternalFrame，设置桌面背景等。 

2. JInternalFrame 轻量级Frame，可以添加到JDesktopPane中

3. JTabbedPane 提供选项卡界面（就像浏览器的那样）

4. JComboBox  下拉列表组合的组件

5. JScrollPane   提供轻量级的scrollable 视图。

6. JTextFiled 文本信息填写格

7. JTable  一个表格，有表头和信息域，接受一个二维数组和一个一维的表头数组
