# Typecho 付费阅读插件 TePass
Typecho 个人支付宝微信收款插件及VIP会员系统，可设置登录可见，VIP会员可见，付费可见。  
付费文章可设置正常价格，VIP会员价格，终身会员价格。    
它跟 TePay 的不同之处在于，TePay 只是一款个人支付宝微信收款插件，带了费用记录和订单查询功能，比较简单和纯粹一些；而 TePass 在此基础了增加了会员这块的功能，可以购买VIP会员，终身会员，设置登录可见，会员可见，VIP会员价格，终身会员价格。  

插件介绍：https://store.pangsuan.com/p/tepass.html  
演示地址：https://store.pangsuan.com/p/tepass.html  
推荐个人微信收款平台：https://payjs.cn/ref/zgpnbd    


##  TePass 购买方式 ##
1：官网：https://store.pangsuan.com/p/tepass.html  
2：QQ：744272645（胖蒜网）  
3、微信：pangsuan_com（不常在线）


## 交易金额限制 ##
**支付宝**：个人用户签约的是当面付的基础版，单笔限额1000元，单日限额50000元，商家用户不限制；  
**微信**：使用的 [payjs.cn][2] ，单笔1000元，单日限额50000元，如果流水大可以申请提高。  


## 环境要求 ##
1、PHP5.6，7.0-7.3；  
2、Nginx 或 Apache；  
3、MySQL 5.5 以上；  
4、Typecho 1.1 以上版本（什么是 [Typecho](https://typecho.org) ？）。  
**强烈建议使用**：阿里云服务器（标准版、系统选Centos、其他配置默认即可后续可升级配置），刚入门选择最低配置或者活动机器均可；不建议使用虚拟主机，支付宝回调消息可能推送不到；推荐使用linux版本宝塔进行管理搭建，完美。   
**另外**：不免费提供程序运行环境搭建工作，如果需要可提供linux下宝塔环境的搭建，收费。

 
## 一、为什么不在TePay上继续开发？ ##  
答：首先改的东西比较多，整合了对之前购买的用户不友好，其次和名字相关，TePay 主要功能就是支付而已，而Pass更多的是表示通过，现在想用的这个插件主要功能就在会员，所以叫 TePass 咯。~  

## 二、之前购买了 TePay 专业版的用户，再次购买有优惠吗？ ##  
答：目前没有任何优惠，但随着日积月累的迭代升级，涨价是肯定的。

## 三、什么时候发布？  ## 
答：2020年2月22日正式发布。 

## 四、能够给个演示站点看看？ ##  
答：本站使用的就是你们将会看到的版本，前台购买界面与TePay一样，用户注册地址为：https://store.pangsuan.com/tepass/signup ，注册登录后就是你看到的会员中心，设置界面需要管理员才能看到。  
1、Typecho爱好者：https://qqdie.com/archives/typecho-teposter-plugin.html  
2、翘课网：https://www.qioke.com/tougao.html  
3、高考学子网：https://payas.cn/archives/8.html  
4、太阳源码：https://www.sunym.top/archives/1804/  
5、临江寒：https://dmxxz.cn/archives/Am-Rudy.html  
6、馒头侠：https://www.mantouxia.com/1085.html  
    

## 五、更新日志 ##
2020-03-09：发布TePass-0.4.0版本，集成微信登录。  
2020-03-06：发布TePass-0.3.0版本，集成QQ、微博、GitHub社交登录。  
2020-03-04：发布TePass-0.2.7版本，优化因站长本人未设置找回密码相关配置，提示不友好的问题。  
2020-03-02：发布TePass-0.2.6版本，增加点击文章登录后返回原文章，点击购买VIP登录后去会员中心；优化其它体验。  
2020-02-29：发布TePass-0.2.5版本，修改后台订单管理菜单的位置，修改进入管理后台的权限。  
2020-02-28：发布TePass-0.2.4版本，新增预留字段，优化后台管理员处理会员和订单的功能。  
2020-02-26：发布TePass-0.2.2版本，优化关键部分代码，增加管理员在后台给用户分配VIP会员功能，优化后台管理的分页体验，付款二维码下方增加显示订单金额。  
2020-02-25：发布TePass-0.2.1版本，增加文章后台付费设置的项目，对用户注册自定义密码进行优化，无需在后台进行修改代码。  
2020-02-23: 发布TePass-0.2.0版本，主要是针对大家对付费逻辑的设置，以前的逻辑是终身会员价不设置，就用VIP会员价，VIP会员价不设置就正常价格，现在更改为不设置即为免费，相应等级会员可见，所以从TePay升级过来的用户要注意，去设置VIP会员价和终身会员价。  
2020-02-22：正式发布TePass-0.1.2版本。


  [1]: https://cdn.jsdelivr.net/gh/mhcyong/backups@latest/usr/uploads/2020/02/23632588.png
  [2]: https://payjs.cn/ref/zgpnbd
