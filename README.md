# ManageDigitalFiles
电子文件管理与共享系统 计算机毕业设计
所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。

<font style="color:#117cee;">🎈</font><font style="color:#117cee;">系统亮点：AI 智能检索、自动生成文件摘要与关键词、文件版本管理与版本对比、Echarts图形化分析、本地存储与 OSS 存储兼容、重复文件检测与存储优化；</font><font style="color:#DF2A3F;"> 类似网盘功能~</font>



<font style="color:#DF2A3F;">注：图片为空，无需纠结。后续需要用自己的oss，重新上传即可。</font>

# <font style="color:#48b378;">一.系统开发工具与环境搭建</font>
## <font style="color:#262626;">1.系统设计开发工具</font>
<font style="color:#262626;">后端使用Java编程语言的Spring boot框架</font>  
<font style="color:#262626;">项目架构：B/S架构</font>  
<font style="color:#262626;">运行环境：win10/win11、jdk17</font>





<font style="color:#48b378;">前端：</font>  
<font style="color:#262626;">技术：框架Vue3 ；UI库：Element-Plus；</font>  
<font style="color:#262626;">开发工具：Visual Studio Code；</font>

---

<font style="color:#48b378;">后端:</font>  
<font style="color:#262626;">技术：Java语言、mybatis-plus、Spring boot框架；</font>  
<font style="color:#262626;">开发工具：IDEA 2025版本；</font>

---

<font style="color:#48b378;">数据库：</font>  
<font style="color:#262626;">数据库：mysql5.7/8.0 </font>  
<font style="color:#262626;">数据库工具：Navicat12版本；</font>

---

# <font style="color:#48b378;">二.系统实现（部分截图）</font>
## 2.1 用户
### 2.1.1AI智能搜索
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322970020-e1736802-06fd-4f71-b086-7f0157f0d1ad.png)

### 2.1.2 首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322970801-bf78dceb-5131-4ac0-91f7-5728056c6343.png)

### 2.1.3 最近
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322970503-17864e5d-6f6a-4340-9776-a3f1b109afc6.png)

### 2.1.4 视频
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322970450-c5ad1606-bca3-4cf4-8349-a08e44de0ab1.png)

### 2.1.5 图片
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322970788-f4dc58a7-1fc6-4d3b-a718-2613ed796ce0.png)

### 2.1.6 文档
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322971571-c5853797-6377-4c8f-a58b-e0208fa34b4e.png)

### 2.1.7 文章资讯
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322973904-c7cfca9a-ae52-41a5-802b-9597948e149d.png)

### 2.1.8 我的文章
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322973232-6fafb07b-6460-4d3e-a17a-507c546caf3e.png)

### 2.1.9 部门管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322972912-0b83a515-93f7-415d-b92f-00962fa86f01.png)

### 2.1.10 组织成员
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322974436-07d3de25-fc2c-4686-a47f-95c24eff2b0b.png)

### 2.1.11权限管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322974433-1890e65b-fca3-4a2d-9e29-f56661347b32.png)

### 2.1.12 文件统计分析
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322974978-3a66dd51-1838-4b60-aaa3-7a36c157e5c6.png)

### 2.1.13 工具
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783323362930-4b61a120-0bef-4606-b99d-0de4d7e8a6f0.png)

### 2.1.14 我的分享
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322977378-33296f4c-6ca8-4ebd-b103-8cdf6e776e65.png)

### 2.1.15 登录日志
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322976571-17d1e75e-8026-41fe-bbb7-64562c5b5ea4.png)

### 2.1.16 垃圾箱
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322977113-6c27cfbb-270b-416d-b481-169194bbe632.png)

## 2.2 管理员
### 2.2.1 账号管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322976663-d22571fc-abb5-4345-8937-b89a909d17cd.png)

### 2.2.2 文件节点
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322977445-ea54fb1e-eccb-4a3b-8eba-92d1f1ebdf68.png)

### 2.2.3 文件分享
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322977990-5a8deb70-7265-47d2-9b9d-59e795e6f0df.png)

### 2.2.4 文件版本
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322977819-8cc2d377-c061-47ce-8560-c176678990c7.png)

### 2.2.5 节点权限
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322978287-0ce44436-7877-46ac-b5e4-5266b11a5e88.png)

### 2.2.6 文件类型统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322978787-a51b9024-1c14-4ab2-86a1-191d96e391a2.png)

### 2.2.7 组织列表
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322978421-dfda7bee-3432-4adf-b599-1e272d15efb4.png)

### 2.2.8 组织成员
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322978728-a9de49f5-0d9b-47d0-82fd-c2541c8feeaa.png)

### 2.2.9 文章管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322978872-f978cff3-b56c-4117-a8d2-7ab427a68d83.png)

### 2.2.10 文章收藏
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322979100-5d93e45d-917b-4d11-9909-ac487067584b.png)

### 2.2.11 登录日志
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322979268-cbbe8f8b-9536-4694-8bfb-bdfe6188c09a.png)

# <font style="color:#48b378;">三.系统代码结构截图</font>
## <font style="color:#262626;">3.1 前端</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322980046-52d268b0-ba48-435f-8d8f-48637a873376.png)

## 3.2 后端
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322980222-7d096007-4174-4edd-a5c6-35a639c07f79.png)

## 3.3 数据库
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1783322979574-d304bad8-52c6-4901-b5d9-90123cda3088.png)

# <font style="color:#48b378;">四.</font><font style="color:#1aad19;">源码获取</font>
<font style="color:#000000;">1.原创系统非商用，非开源，非无偿。</font>

<font style="color:#000000;">2.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>

