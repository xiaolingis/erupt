Chinese &nbsp; | &nbsp; [English](./README-EN.md)  

<p align="center"><img src="./erupt-web/src/main/resources/public/erupt.svg" height="150" alt="logo"/></p>
<h1 align="center"> Erupt Framework &nbsp; 🚀 &nbsp; 通用后台管理框架 </h1>
<h3 align="center">零前端代码，几行 Java 注解，搞定后台管理系统</h3>
<h3 align="center"><a href="https://erupt.xyz" target="_blank">https://www.erupt.xyz</a></h3>

---

<p align="center">
    <a href="https://www.erupt.xyz" target="_blank"><img src="https://img.shields.io/badge/Erupt-Framework-brightgreen" alt="Erupt Framework"></a>
    <a href="https://www.oracle.com/technetwork/java/javase/downloads/index.html"><img src="https://img.shields.io/badge/JDK-8+-green.svg" alt="jdk 8+"></a>
    <a href="./LICENSE"><img src="https://img.shields.io/badge/license-Apache%202-blue" alt="license Apache 2.0"></a>
    <a href="https://gitee.com/erupt/erupt"><img src="https://gitee.com/erupt/erupt/badge/star.svg?theme=dark" alt="Gitee star"></a>
    <a href="https://gitee.com/erupt/erupt"><img src="https://gitee.com/erupt/erupt/badge/fork.svg?theme=dark" alt="Gitee fork"></a>
    <a href="https://github.com/erupts/erupt"><img src="https://img.shields.io/github/stars/erupts/erupt?style=social" alt="GitHub stars"></a>
    <a href="https://github.com/erupts/erupt"><img src="https://img.shields.io/github/forks/erupts/erupt?style=social" alt="GitHub forks"></a>
    <a href="https://github.com/erupts/erupt"><img src="https://img.shields.io/github/repo-size/erupts/erupt" alt="size"></a>
</p>

<p align="center">
    <a href="https://github.com/erupts/erupt">Github 仓库</a> &nbsp; | &nbsp; 
    <a href="https://gitee.com/erupt/erupt">Gitee 仓库</a> &nbsp; | &nbsp; 
    <a href="https://www.erupt.xyz" target="_blank">官方网站</a> &nbsp; | &nbsp; 
    <a href="https://www.yuque.com/yuepeng/erupt" target="_blank">使用文档</a> &nbsp; | &nbsp; 
    <a href="https://www.yuque.com/yuepeng/erupt/bdiq6o" target="_blank">贡献指南</a> &nbsp; | &nbsp; 
    <a href="https://www.erupt.xyz/demo" target="_blank">在线体验</a>
</p>

<p align="center">
    QQ交流群：<a href="https://jq.qq.com/?_wv=1027&k=MCd4plZ0">821389129🔥</a> 加群可获取erupt-tpl 与 erupt-generator 模块
</p>

---

##  简介 | Intro
Erupt 是一个低代码 **全栈类** 框架，它使用 **Java 注解** 动态生成页面以及增、删、改、查、权限控制等后台功能。

零前端代码、零 CURD、自动建表，仅需 **一个类文件** + 简洁的注解配置，快速开发企业级 Admin 管理后台。

提供企业级中后台管理系统的全栈解决方案，大幅压缩研发周期，专注核心业务。

> 完美取代 **代码生成器**，开发后台管理系统更优解！

## 特性 | Features
+ **易于上手**：会简单的 **Spring Boot** 基础知识即可。
+ **使用简单**：仅需了解 **@Erupt** 与 **@EruptField** 两个注解即可上手开发
+ **代码简洁**：前端零代码，后端 template、controller、service、dao 都不需要，**仅需一个类文件**即可。
+ **敏捷开发**：仅单个`.java`文件即可实现后台管理功能，专注业务与核心功能的研发。
+ **快速迭代**：需求变更仅需修改或添加注解配置即可，迭代速度比需求讨论速度还快。
+ **功能强大**：动态条件处理，支持增删改查等功能代理接口，Session存储机制选择，行为日志记录等。
+ **自动建表**：依托于JPA可自动帮你完成数据库建表相关工作。
+ **低侵入性**：几乎所有功能都围绕注解而展开，不影响Spring Boot其他功能或三方库库的使用。
+ **多数据源**：MySQL、Oracle、SQL Server、PostgreSQL、H2，甚至支持**MongoDB**。
+ **多种组件**：支持滑动输入、时间选择、开关、图片上传、代码编辑器、自动完成、树、多选框、地图等23类组件
+ **丰富展示**：普通文本、**二维码**、链接、图片、HTML、代码段、iframe、swf等
+ **代码生成**：erupt代码已经足够简洁，代码生成器可进一步提升开发效率。
+ **高扩展性**：支持自定义数据源实现、自定义页面、动态权限管理、**自定义OSS**等。
+ **界面美观**：每个交互都精心设计，产品思维打磨，只为了更好的操作体验。
+ **权限管理**：用户管理、角色管理、组织管理、菜单管理、登录日志、操作日志等。
+ **高安全性**：可靠的安全机制，登录白名单，权限验证，注解项检查，细颗粒度权限控制，为你的数据保驾护航。
+ **前后端分离**：后端与前端可分开部署
+ **响应式布局**：支持PC端手机端等各种规格的设备中使用。
+ **无需二次开发**：仅需引用 jar 包即可。

## 演示截图 | Screenshot
![](./readme/index.png)

![](./readme/seer.png)
<table>
    <tr>
        <td><img src="readme/goods.png"/></td>
        <td><img src="readme/chart.png"/></td>
    </tr>
    <tr>
        <td><img src="readme/code.png"/></td>
        <td><img src="readme/job.png"/></td>
    </tr>
    <tr>
        <td><img src="readme/complex.png"/></td>
        <td><img src="readme/complex-edit.png"/></td>
    </tr>
    <tr>
        <td><img src="readme/tpl.png"/></td>
        <td><img src="readme/role.png"/></td>
    </tr>
    <tr>
        <td><img src="readme/component.png"/></td>
        <td><img src="readme/component-edit.png"/></td>
    </tr>
</table>


## 为什么要做 Erupt ?
无论开发怎样的系统，都需要配套的管理后台做数据支撑，是软件开发中必不可少的一环，但实际开发中存这无法规避的痛点，如：开发效率低下、接口对接繁琐、界面差强人意、代码重复、有安全漏洞，导致开发成本极高。

虽然近些年来 **代码生成器** 成了后台开发的新宠，但它真的是后台开发的最优解吗？   
代码生成器的本质还是生成繁琐的前端与后台代码，一旦修改后期生成的代码很难合并，想想 Mybatis-Generator，基本上就是一次性的东西，虽然减轻了部分工作，可解决方式并非最佳。

开发后台管理系统大部分情况下只想做个普通的增删改查界面，用于数据管理，类似下面这种：
![result](readme/view.png)
![result](readme/edit.png)

``` java
@Erupt(
       name = "简单的例子",
       power = @Power(importable = true, export = true)
)
@Table(name = "t_simple")   //数据库表名
@Entity
public class Simple extends BaseModel {

    @EruptField(
            views = @View(title = "文本"),
            edit = @Edit(title = "文本", notNull = true, search = @Search)
    )
    private String input;

    @EruptField(
            views = @View(title = "数值", sortable = true),
            edit = @Edit(title = "数值", search = @Search)
    )
    private Float number;

    @EruptField(
            views = @View(title = "布尔"),
            edit = @Edit(title = "布尔")
    )
    private Boolean bool;

    @EruptField(
            views = @View(title = "时间"),
            edit = @Edit(title = "时间", search = @Search(vague = true))
    )
    private Date date;

}
```

[功能体验](https://www.erupt.xyz/#!/contrast)

这个界面虽然用 Vue + Ant-Design + SSM 也能做出个大概，但仔细观察会发现它有大量细节功能如：

+ 有按钮可以查询、新增、批量删除、excel 导入导出
+ 可以对数据做筛选、隐藏某列、按某列排序
+ 表格有分页与汇总，可预览单行数据
+ 多种组件、有校验规则

全部实现这些仅前端就需要大量的代码，后端的接口与业务逻辑更不在少数。

但可以看到，用 erupt 只需要 **30几行** 代码就能完成，你不需要了解 Angular / React / Vue / Jquery 也不需要了解 JavaScript / HTML / CSS，甚至不需要了解 Spring MVC / Mybatis / SQL，即便没学过 erupt 也能猜到大部分配置的作用，只需要简单配置就能完成所有后台页面开发。

这正是建立 erupt 的初衷，对于大部分常用页面，应该使用最简单的方法来实现，甚至不需要学习各种框架和工具，专注核心业务，告别 996，省下的时间做自己喜欢做的事，从此不再因为繁琐的后台开发而焦头烂额。


## 下载使用 | Download
下载最新的JAR或通过Maven获取。
```xml
<!--用户权限管理-->
<dependency>
  <groupId>xyz.erupt</groupId>
  <artifactId>erupt-upms</artifactId>
  <version>LATEST-VERSION</version>
</dependency>
<!--接口数据安全-->
<dependency>
  <groupId>xyz.erupt</groupId>
  <artifactId>erupt-security</artifactId>
  <version>LATEST-VERSION</version>
</dependency>
<!--后台WEB界面-->
<dependency>
  <groupId>xyz.erupt</groupId>
  <artifactId>erupt-web</artifactId>
  <version>LATEST-VERSION</version>
</dependency>
```
[详细使用步骤](https://www.yuque.com/yuepeng/erupt/tpq1l9)

## 模块说明 | Module
```lua
erupt
├── erupt-annotation -- 核心注解声明
├── erupt-core -- 核心功能实现
├── erupt-data -- 数据实现包
     ├── erupt-jpa -- 关系型数据库erupt实现
     └── erupt-mongodb -- mongodb数据库erupt实现
├── erupt-job -- 定时任务功能
├── erupt-security -- 接口数据安全模块
├── erupt-upms -- 用户权限管理
└── erupt-web -- 前端页面

erupt-site -- erupt官方网站 https://github.com/erupts/erupt-site

erupt-pro -- 暂未开放 star 超过 1K 开放 erupt-tpl 模块与 erupt-generator 模块
├── erupt-bi -- 通过 sql 加 js 混编实现动态报表，支持多数据源，支持十几种图表
├── erupt-tpl -- 支持在 erupt 中自定义页面，自定义图表，自定义模板等功能，模板引擎支持 freemarker / thymeleaf / 原生H5
└── erupt-generator -- 代码生成器，通过简单配置，生成 erupt 代码段

erupt-web-angular -- 暂未开放 erupt 前端源码

```

## 技术体系 | Technology system
**后端：**
Java 8、 ScriptEngine、 Annotation、 JDBC、 Reflect、 Spring Boot、 JPA、 Hibernate、 Quartz、 Gson、 Lombok、 POI ...

**前端：**
JavaScript、 H5、 MVVM、 Router、 Angular CLI、 Angular、 NG-ZORRO、 NG-ALAIN、 G2Plot、 RxJS、 TypeScript、 Less ...

## 更新计划 | Future vision
+ 增加按钮级权限控制 （已支持 ✔️）
+ 支持更多的组件
+ 大数据分库分表支持
+ 多种不同的登录形式
+ 主题色更改
+ 国际化支持
+ 流程引擎支持

## 在线体验 | Demo
演示地址：https://www.erupt.xyz/demo  
账号密码：`guest / guest`

**支持主流 4 款现代浏览器，以及 Internet Explorer 11+，可直接运行在 Electron 等基于 Web 标准的环境上**

<table width="100%">
    <tr>
        <th width="20%" align="center"><img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" /> <br> Edge / IE </th>
        <th width="15%" align="center"><img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" /><br> Firefox </th>
        <th width="15%" align="center"><img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" /> <br> Chrome </th>
        <th width="15%" align="center"><img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" /> <br> Safari </th>
        <th width="15%" align="center"><img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" /> <br> Opera </th>
        <th width="20%" align="center"><img src="https://cdn.jsdelivr.net/gh/alrra/browser-logos/src/electron/electron_48x48.png" alt="Electron" width="24px" height="24px" /> <br> Electron </th>
    </tr>
    <tr>
        <td align="center">Edge 16 / IE 11+</td>
        <td align="center">522</td>
        <td align="center">57</td>
        <td align="center">11</td>
        <td align="center">44</td>
        <td align="center">Chromium 57</td>
    </tr>
</table>

## 使用文档 | Documentation
https://www.yuque.com/yuepeng/erupt

## 代码样例 | Example Code
gitee: &nbsp; https://gitee.com/erupt/erupt-example   
github: https://github.com/erupts/erupt-example

## 开源推荐 | Recommend
[`zeta-api`：通过XML配置快速创建api接口与文档，安全且高效，快速开发必备！](https://github.com/erupts/zeta-api)

## 加入讨论 | Join Discussion
<table width="100%">
    <tr>
        <td width="50%"><img src="readme/group/qq-1.jpeg" alt=""></td>
        <td width="50%"><img src="readme/group/wexin-1.jpeg" alt=""></td>
    </tr>
</table>

## 捐赠 | Donate
此框架服务器，域名，空间，人工等费用一直由作者本人自掏腰包并持续维护，开源不易，一杯咖啡也是爱。
<table width="100%">
    <tr>
        <td width="50%"><img src="readme/wepay.jpeg" alt=""></td>
        <td width="50%"><img src="readme/alipay.jpeg" alt=""></td>
    </tr>
</table>


**Erupt 使用 Apache License 2.0 协议，源代码完全开源，无商业限制。 开源不易如果喜欢请给作者 Star 鼓励 👇**

- **Github**：https://github.com/erupts/erupt

- **Gitee**：https://gitee.com/erupt/erupt

---

<p align="right">
作者 ：YuePeng / <a href="mailto:erupts@126.com">erupts@126.com</a>
</p>
<br>