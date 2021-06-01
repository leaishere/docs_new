# 4步上手文档中心

## Step1:注册账号、申请仓库 	

使用**ucloud邮箱**注册github账号     >>>    联系主仓库的管理者冯业浩新建仓库     >>>      查收邀请邮件，前往仓库

[详细内容>>](before_work)

## Step2:开始写文档

#### 	1. 查看**产品文档仓库/API文档仓库** [仓库列表>>](https://github.com/UCloudDocs?tab=repositories)

#### 	2. 了解**仓库内容结构** [仓库内容详解>>](repository)

```markdown
1. _sidebar.md：用于控制左侧目录
2. overview.md：建议仓库提供的概览页，方便创作者对外分享也方便用户整体概览
3. images文件夹：用户存储所有文档用，引用方式如下：
![图片注释](/images/图片.png)
		
4. 文件夹/markdown文件：各层级关系的文档
```

![画板](images/画板.jpg)



## Step3:实时预览文档前往 

我们支持实时预览。仓库内的变更都可以实时在[发布页面](https://cms.docs.ucloudadmin.com/ucpublishnew.html)上点击“前往预览”进行查看。



## Step4:自由发布

发布地址：[点击这里](https://cms.docs.ucloudadmin.com/ucpublishnew.html)![image-20200113184021386](../docs_new/images/image-20200113184021386.png)



## 常见问题：

### Q：为什么我没有发布权限？

### A：请确认以下几点：

- 是否对仓库具有**master权限**。没有？联系**平台PD**
- 是否**公开**注册邮箱？
- 账号的**Primary邮箱**是否是**UCloud注册邮箱**？
-  是否完成一次 **commit**

------

## 附录_可复制的markdown模版

- [_sidebar.md](#_sidebar.md)
- [overview.md](#overview.md)
- [tabs标签模版](#tabs标签模块)
- [收起展开html语法](#收起展开html语法)

### _sidebar.md

``` markdown
<div class="sidebar_title icon__uhost"> 云主机 UHost</div>                 <!-- 产品名称+icon -->
<!-- 空行不要删除！！！ -->           <!-- 空行不要删除！！！ -->            <!-- 空行不要删除！！！ -->
* [概览](/uhost/README)
* 产品简介
    * [什么是云主机](/uhost/introduction/concept)                  <!-- 层级缩进=4个空格 -->
    * [产品优势](/uhost/introduction/advantages)
    * [功能简介](/uhost/introduction/functions)
    * [计费说明](/uhost/introduction/charge)
    * 主机
        * [地域与可用区](/uhost/introduction/uhost/az)
        * [机型与CPU平台](/uhost/introduction/uhost/type_new)
        * [特性](/uhost/introduction/uhost/feature)
        * [订单构成](/uhost/introduction/uhost/lifecycle)
        * [配额](/uhost/introduction/uhost/quota)
        * [机型与规格](/uhost/introduction/uhost/type)
```



### README.md

```markdown
# 概览
* 产品简介
    * [什么是云主机](/uhost/introduction/concept)         <!-- 若写目录，可直接复制sidebar -->
    * [产品优势](/uhost/introduction/advantages)
    * [功能简介](/uhost/introduction/functions)
    * [计费说明](/uhost/introduction/charge)
    * 主机
        * [地域与可用区](/uhost/introduction/uhost/az)
        * [机型与CPU平台](/uhost/introduction/uhost/type_new)
```
> ### 概览页只能写目录？
>
> 当然不是，平台只是给出最低配的建议，以方便那些需要对外分享文档目录的创作者。平台非常希望广大创作者发挥自己的才智，使用md语法和平台提供的丰富样式来构建更有价值的概览页。



### Tabs标签模块

``` markdown
<!-- tabs:start -->

#### ** 第一个标签的标题 **

第一个标签的内容：

* 标题1
* 标题2

#### ** 第二个标签的标题 **

第二个标签的内容：

* 标题1
* 标题2

#### ** 第三个标签的标题 **

第三个标签的内容：

* 标题1
* 标题2
  <!-- tabs:end -->
```



### 收起展开html语法

```HTML
<details>
  <summary>点击时的区域标题</summary>
​```
这是折叠的代码1
这是折叠的代码2
​```
</details>
```

#### 【demo】

<details>
  <summary>点击查看</summary>
我是详情内容
</details>
------



### 【参考资料】

[Md语法说明](https://www.jianshu.com/p/40ba812dd973)  

[范例_ULB文档](https://github.com/UCloudDocs/UCloud-document/tree/master/network/ulb)

[Github简明教程](https://github.com/UCloudDocs/UCloud-document/tree/master/network/ulb)

