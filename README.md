# PHP网站系统核心基类和接口库 #

## 项目依赖 ##

## 使用说明 ##
 * 需要使用定义WEB系统根目录的静态常量ROOT。
 * 如果使用页面基类，则需要定义页面基本使用到的Smarty常量，如下：
 	* SMARTY_PATH：Smarty库的绝对路径。
 	* SMARTY_TEMPLATES：Smarty页面模板的默认路径。
 	* SMARTY_CACHE：Smarty缓存的绝对路径，要求写权限。参见Smarty的基本安装（[中文](http://www.php100.com/manual/smarty/installing.smarty.basic.html)、[英文](http://www.smarty.net/quick_install)）。

## 分发目录的说明 ##

## 版本更新记录 ##

### 0.1.1 ###
 * 页面基类中增加常用常量的赋值。

### 0.1.0 ###
 * 重构了数据层基类中数据库工具性方法。

### 0.0.4 ###
 * 增加了页面拦截和页面菜单的提供器接口定义。
 * 页面基类中增加了页面拦截和页面菜单的基类定义。

### 0.0.3 ###
 * 修改了HttpContext类，使其能够设置用户身份对象。
 * 优化了WebPage类，使其优先使用已经定义了的用户身份对象。

### 0.0.2 ###
 * 修订了数据层基类的查询方法在没有返回值时报错的BUG。

### 0.0.1 ###
 * 初步框架化了PHP网站系统核心基类和接口。

## 作者信息 ##
 * 电子邮件：peigong@foxmail.com
 * 微博地址：[http://weibo.com/u/3030510210](http://weibo.com/u/3030510210)
 * 博客地址：[http://www.peigong.tk](http://www.peigong.tk)
 * 项目地址：[https://github.com/peigong/php-site-core](https://github.com/peigong/php-site-core)
