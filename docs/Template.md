# 可复制的markdown模版

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

