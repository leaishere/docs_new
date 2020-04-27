# 开始使用Github创作您的UCloud Doc


## 【新功能发布日志】

| 发布日期   | 发布内容                   | 使用说明                                              | 发布人 |
| ---------- | -------------------------- | ----------------------------------------------------- | ------ |
| 2019-12-03 | 左边栏支持添加产品icon     | [前往查看](https://leaishere.github.io/docs_new/icon) | 李安   |
| 2020-01-13 | 功能更新：支持自由发布     | [前往查看](#step4自由发布)                            | 李安   |
| 2020-01-13 | 功能更新：支持更多语言高亮 | [前往查看](faq)                                       | 李安   |
| 2020-01-13 | 功能更新：支持tabs样式     | [前往查看](faq)                                       | 李安   |
| 2020-01-15 | 指南更新：提供markdown模版 | [前往查看](#附录_可复制的markdown模版)                | 李安   |

---



## 快速阅读

> - ### 快速上手 UCloud Docs
>
>   - [4步上手文档中心！](#step1注册账号申请仓库)
>   - [可复制的markdown模版](#附录_可复制的markdown模版)
>
> - ### 常见问题
>
>   - [如何使用超链接](faq#6超链接)
>   - [合理使用Tips样式](faq)
>   - [更多语法支持高亮](faq)
>   - [平台支持Tabs](faq)
>   - [左侧导航目录缺失？](faq)
>   - [如何自定义文章排序](faq)
>
> - ### 完全新手？我第一次用github/第一次写文档
>
>   - [【推荐阅读】《助你5步创建技术文档》](https://plan.io/blog/technical-documentation/)
>   - [PD如何管理仓库？](duty)
>   - [第一次用github写文档？](create)
>   - [有没有推荐的md编辑器？](typora_github)
>
> - ### 意见收集：若您对指南的内容有更好的意见和建议，欢迎告诉我们
>
>   [点击此处提交反馈](https://github.com/leaishere/docs_new/issues/1)
>   
> - ### 维护人员
>
>   - [产品文档维护及发布](https://ushare.ucloudadmin.com/pages/viewpage.action?pageId=17798669)：由产品文档负责人们分管
>   - API文档维护：徐晓路
>   - 平台导航维护及发布：李安
>   - Github建仓：冯业浩
>   - Github仓库管理员维护：李安



---

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

