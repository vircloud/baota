# 寶塔

寶塔 Linux LNMP v2.8.9 一鍵安裝腳本

用法：

     mv bt.sh install.sh
     
     chmod +x install.sh
     
     ./install.sh
     


此版本為寶塔舊版，支持面板 SSL，支持 CentOS 6&7。

包含軟體：Tengine-2.2.0/Nginx1.8-1.10/Apache2.4/MySQL5.5-5.7/PHP5.2-7.0/Pure-Ftpd1.0.45，可在安裝中選擇，安裝後會有登錄信息提示。

依據主機性能，全程安裝需 30m ~ 1h 時間。

由於官方已更新服務器文件，因此需要替換 /www/server/nginx/ 目錄下的 nginx.conf 文件，否則面板打不開。

面板亮點：一键 LAMP/LNMP、创建网站 FTP、数据库、SSL；安全管理，计划任务，文件管理，PHP 多版本共存及切换，一键开启 Tomcat 环境。

寶塔管方網站：https://www.bt.cn/
