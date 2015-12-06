# MavenTest
Maven to build, selenium + TestNG + eclipse framework to do automation testing

File structure:

-com.netease.gacha.api  此处为接口调用实现
---common_API.java
---Discover_API.java
---GList_API.java
---ParseUtil.java

-com.netease.gacha.dataprovider     此处为测试数据参数化实现

-com.netease.gacha.suit.discover     此处为测试用例suit
-com.netease.gacha.suit.Glist     
-com.netease.gacha.testdata     此处存放测试数据

-com.netease.settings     此处一些全局配置
--GlobalSettings.java
---LogTools.java
-com.netease.util     此处为相关工具的实现
---HttpClientHelper.java
---MD5.java
---Time.java
log4j.properties

from the blog: - 《手把手教你用Eclipse+TestNG搭建接口自动化测试框架》http://qa.blog.163.com/blog/static/190147002201510275306185/
