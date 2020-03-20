# UC-Login

一，安装CentOS7，启动

安装ifconfig：【参考：https://www.cnblogs.com/dxqNet/p/11479395.html】
  yum install net-tools.x86_64
  yum install ifconfig 
  如果出现 VMware下centOS yum报错cannot find a valid baseurl or repo:base 解决方法
  方法：
　　1、打开 vi /etc/sysconfig/network-scripts/ifcfg-eth0（每个机子都可能不一样，但格式会是“ifcfg-eth数字”），把ONBOOT=no，改为ONBOOT=yes
　　2、重启网络：service network restart
  
  
  
