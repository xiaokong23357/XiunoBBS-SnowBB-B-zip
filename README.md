# XiunoBBS-B-zip

此开源库收集了xiunobbs正式版的安装包

[推荐查看这个](https://github.com/xiaokong23357/XiunoBBS-B-zip/blob/main/JK-README.md)

关于该库的个人开源：https://github.com/jiix/xiunobbs

- Xiuno来源介绍

Xiuno 这个名字来源于圣斗士星矢白羊座的黄金圣斗士修罗，他的攻击速度和战斗力是十二宫最强的，他是速度和力量的化身; 在佛教里面，修罗为六道之一，英文：Shura，处于人道和天道之间的一道，半人半神，性情刚烈，好战斗，梵语中，修罗意味端庄，气宇轩昂（阿为否定，阿修罗意思为丑陋好斗)。我们取其寓意，希望 Xiuno 变得越来越强，越来越快。

- Xiuno BBS 4.0 简介

Xiuno BBS 4.0 是 2016 年诞生的，国产、小巧、精悍、基于目前新流行的技术、有着前沿产品理念的、主要采用 PHP 开发的、遵照严格的命名和编码规范的 web 产品，它不仅仅是一个论坛，还是一个良好的二次开发平台。在开发效率上，基于框架开发，不如基于成熟的产品开发。

- Xiuno BBS 4.0 功能介绍

1. 前端采用BootStrap 4+JQuery 3，响应式布局，自适应手机，平板，PC 设备，不再需要单独开发移动版本。
2. 对 Bootstrap 4 进行了增强和兼容，比如增加 $('#submit').button('xxx').delay(3000).location('xxx.php') 的连续操作支持，修正 .row .row 嵌套导致的间距、手机下的间距过大等问题。
3. xiuno.js 采用了 xn. 命名空间，不再担心 js 命名冲突，完善了对常用的 php 函数的实现。
增加了通用的 $.each_sync() 方法，从客户端避免 ajax 并发导致的服务端并发写数据问题，简化了服务端逻辑。
4. 不再支持 IE8 和以下版本，全面拥抱移动端，不用再用琢磨恶心的 css hack。
5. 不再强制要求 URL-Rewrite，同时支持多种 URL 格式：user-login.htm /user/login 。
6. 图片缩略、裁切放到了客户端，不再依赖服务端 GD 库。
7. 同时支持 Session 和 Token 方式登录，可以返回 json 数据，方便 REST 接口开发。
8. 插件机制采用 AOP 机制，支持 hook + overwrite 方式，方便插入，和覆盖，非常方便二次开发，并且不影响性能，不影响编译。
9. db 层采用了更加方便的接口，可以同时支持 SQL 和 NoSQL 的方式操作数据。
10. 论坛功能上更加的精简，更多功能采用插件的方式进行扩充。
11. 引入了语言包，自带简体、繁体、英文三个版本。
12. 插件中心正式开启，开发者可以入驻，开发收费插件。
13. 帖子支持 txt html markdown ubb 多种格式，自带适度整合的 UMEditor 插件，修正了 UM 在 Bootstrap 4 下的很多问题。
14. xiunophp 4.0 这个框架合并成了一个文件 xiunophp.min.php，只需要一个 include 就可以开始使用里面提供的方便的函数和全局变量。
15. Maybe Xiuno BBS 4.0 is the lastest big version.

- Xiunuo BBS 4.0 性能介绍

1. 采用静态语言编程风格，充分发挥 PHP7 OPCache 的威力。
2. 专门针对 BBS 业务的索引优化和适度的缓存。
3. 大量的运算放到了客户端，并发问题尽量由客户端控制。
4. 作者十多年从业经验带领您绕过雷区。

- Xiuno BBS 4.0 版权介绍

Xiuno BBS 4.0 采用 MIT 协议发布，您可以自由修改、派生版本、商用而不用担心任何法律风险（修改后应保留原来的版权信息）.
以上内容均来自于百度百科：https://baike.baidu.com/item/xiuno/9012958

- 个人开发者修改版【部分插件不兼容】

https://github.com/jiix/xiunobbs

注意事项
请注意XiunoBBS_4.0.4是Xiuno最后一个版本
安装完成后一定要将install文件夹删除
强烈建议安装Nginx或Apache防火墙或其他防护程序，修复X-Frame-Options漏洞，PHP设置防跨站
建议在安装使用前点击下方链接进行查阅安全漏洞
https://www.cnvd.org.cn/flaw/flawListByManu/74953
