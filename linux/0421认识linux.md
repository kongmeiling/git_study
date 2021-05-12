# 1、养成的习惯

## （1）工作习惯

①建立目录，分类明确

d:\package\新建软件包安装目录

d:\doc\你要存储的文档

e:\soft\你安装的软件目录

**[注意]**

​     e:\soft\不能有任何中文,括号,空格的文件夹存在,如果要区分,采用“_”。

②看到一个弹出窗口,先读一读是什么,哪怕他是英文,先读懂或尽量读懂,不要一上来就看着"确定"就想点

## （2）学习习惯

①英文在it中重要但不能成为制约你的因素,你只要不**懒**,遇到不会的查,慢慢读起来,撬开你羞涩的嘴,建议你可以在电脑上安装"有道词典"

② 学会百度

③ 学it没捷径,都是磨出来的,所以坚持

④建议你的电脑安装屏幕录制的相关软件,老师上课时你可以录下屏

⑤自己总结并自己给自己讲课

⑥冷静下来玩技术



# 2.了解linux的世界

含Unix,stallman,GNU,linux,linus,linux发行版



历史：C语言 → unix → stallman（GNU计划） → linus（GZT、内核开源）

​         20c60s   20c70s            自由软件之父              linux之父（CentOS）



注意：①开源即是开放源代码（www.oschina.net 是中国最大的开源系统）

​           ②linux操作系统主要在服务器上，作为服务器的操作系统使用

​           ③个人用：windows；        企业用：unix（Solaris/AIX/HP-UX)、lunix  



# 3.vm虚拟机

门道采用虚拟机的方案来完成linux的教学

你把这个虚拟机想成是我申请的阿里云服务器并且机房在杭州某机房中

 

# 4.连接想要的服务器

我只要知道服务器的ip,用户名,密码就可以连

原则上我可以连世界上任何暴露出来的服务器

 

# 5.安装centos6和centos7



## （1）差异点

|          |                          CentOS6.9                           |                  CentOS7                  |
| :------: | :----------------------------------------------------------: | :---------------------------------------: |
| 查IP地址 | 打开→在黑底点击鼠标右键→点击“open in Terminal”→输入“ifconfig” | 打开登陆后直接输入“ip addr”，回车即可查看 |



##  （2）相同点

①连接终端。操作步骤：双击PuTTy → 在“Host  Name”中输入IP地址 → 在“Saved  Sessions”重命名并保存（Save） → Open → 双击重命名；

②更改字体大小及颜色。操作步骤：双击PuTTy → 右击左上图Change  Settings → 点击Window中的Appearance → 在Font  settings中选择change → 更改设置并确点击window中的Colors → 选择Default  Foreground来更改颜色 → 点击Session → 在Saved  Sessions中选择之前重命名IP并保存（save） → 点击Apply即可。



# 6.远程连接工具

在linux的世界,远程连接工具非常多，你喜欢哪个就用哪个，从市面了解来看,

一般用putty，SSH，CRT，XShell