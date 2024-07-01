# Gmeek 博客相关代码和设置的简单化教程

---

> [!NOTE]
> ###  阅前提示
> **本篇文章部分内容取自 [Meekdai的博客](https://blog.meekdai.com/) 请大家支持！**<br>
> **本篇文章针对萌新搭建完成Gmeek博客后需要了解的一系列Markdown基本语法及可用扩展。**<br>
> **因本文章是专门针对萌新的教程，每个章节都附带使用教程，所以看起来相对简单透彻。**

---

# 目录

---

 ## Markdown基本语法

> ### 1、[标题](#标题)
> ### 2、[引用](#引用)
> ### 3、[有序列表](#有序列表)
> ### 4、[无序列表](#无序列表)
> ### 5、[任务列表](#任务列表)
> ### 6、[代码块](#代码块)
> ### 7、[换行](#换行)
> ### 8、[数学公式](#数学公式)
> ### 9、[表格](#表格)
> ### 10、[横线](#横线)
> ### 11、[链接绑定](#链接绑定)
> ### 12、[点击跳转](#点击跳转)
> ### 13、[超链接](#超链接)
> ### 13、[字体样式](#字体样式)
---
## Issues代码

> ### 1、[图片对齐](#图片对齐)
> ### 2、[文本对齐](#文本对齐)
> ### 3、[添加B站视频](#添加B站视频)
> ### 4、[强调关键信息](#强调关键信息)
> ### 5、[自定义链接名称](#自定义链接名称)
> ### 6、[下拉列表](#下拉列表)

---

## config设置

> ### 1、[在主页右上角添加外部链接](#在主页右上角添加外部链接)


# 文章

## Markdown基本语法

----

### 标题

**代码：**

```
# BiaoTi

## BiaoTi

### BiaoTi

#### BiaoTi

##### BiaoTi

###### BiaoTi
```

**演示：**

# BiaoTi

## BiaoTi

### BiaoTi

#### BiaoTi

##### BiaoTi

###### BiaoTi

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 引用

**代码：**

```
> 此时此刻显示在你面前的是引用
```

**演示：**

> 此时此刻显示在你面前的是引用

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 有序列表

**代码：**

```
1. 第一段
2. 第二段
3. 第三段
```

**演示：**

1. 第一段
2. 第二段
3. 第三段

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 无序列表

**代码：**

```
- 第一章
- 第二章
  - 第一节
  - 第二节
    - 第一段
    - 第二段
```

**演示：**

- 第一章
- 第二章
  - 第一节
  - 第二节
    - 第一段
    - 第二段

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 任务列表

**代码：**

```
- [ ] 在月球向地球蹦极
- [ ] 单手举起一座山
- [ ] 时速1w公里的跑酷运动
- [ ] 赚到10w个小目标
- [x] 做白日梦
```

**演示：**

- [ ] 在月球向地球蹦极
- [ ] 单手举起一座山
- [ ] 时速1w公里的跑酷运动
- [ ] 赚到10w个小目标
- [x] 做白日梦

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 代码块

**代码：**

```
3个 `
添加内容
3个 `
```

**演示：**

```
/<div align=center>
<img src="图片链接" 
width="100" height="100">
</div>
```

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---
### 换行

**代码：**

```
<br>
```

**演示：**

**未添加br代码**<br>
这是第一行 这是第二行
<br>
<br>**已添加br代码**<br>
这是第一行<br>这是第二行<br>这是第三行

> 使用说明：将代码`<br>`添加到句子尾部即可，若想要空出一行，可空出一行后将`<br>`添加到下一段句子的前端。<br>
> 例如：<br>
> **未添加br代码**`<br>`<br>
> 这是第一行 这是第二行<br>
> `<br>`<br>
> **已添加br代码**`<br>`<br>
> 这是第一行`<br>`<br>这是第二行`<br>`<br>这是第三行

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 数学公式

普通数学公式

**代码：**

```
$$
\frac{\partial f}{\partial x}= 2\sqrt{a}x
$$
```

**演示：**

$$
\frac{\partial f}{\partial x}= 2\sqrt{a}x
$$

行类数学公式

**代码：**

```
$\theta=x^2$ 
```

**演示：**

$\theta=x^2$ 

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 表格

**代码：**

``` 
| 序号 |         目标         |            完成感受            |
| :--: | :------------------: | :----------------------------: |
|  1   |   在月球向地球蹦极   |  梦里啥都能干，但千万别尿尿。  |
|  2   |    单手举起一座山    |  梦里啥都能干，但千万别尿尿。  |
|  3   | 时速1w公里的跑酷运动 |  梦里啥都能干，但千万别尿尿。  |
|  4   |   赚到10w个小目标    | 白日梦里啥都有，但千万别尿尿。 |
|  5   |       做白日梦       |             额....             | 
```

**演示:**

| 序号 |         目标         |            完成感受            |
| :--: | :------------------: | :----------------------------: |
|  1   |   在月球向地球蹦极   |  梦里啥都能干，但千万别尿尿。  |
|  2   |    单手举起一座山    |  梦里啥都能干，但千万别尿尿。  |
|  3   | 时速1w公里的跑酷运动 |  梦里啥都能干，但千万别尿尿。  |
|  4   |   赚到10w个小目标    | 白日梦里啥都有，但千万别尿尿。 |
|  5   |       做白日梦       |             额....             |

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 横线

**代码：**

```
---
```

**演示：**

---

以上是输入三个"-"减号所构成的。

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 链接绑定

**代码：**

```
链接单次使用

[MyBlog](https://diyingisader.github.io/zang_diying.github.io/  "这是我的博客")

链接多次使用

第一次使用 [MyBlog][id]

第二次使用 [MyBlog][id]

第三次使用 [MyBlog][id]

[id]:https://diyingisader.github.io/zang_diying.github.io/  "这是我的博客"
```

**演示：**

链接单次使用

[MyBlog](https://diyingisader.github.io/zang_diying.github.io/  "这是我的博客")

链接多次使用

第一次使用 [MyBlog][id]

第二次使用 [MyBlog][id]

第三次使用 [MyBlog][id]

[id]:https://diyingisader.github.io/zang_diying.github.io/  "这是我的博客"

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 点击跳转

**代码：**

```
详细清看[数学公式](#数学公式)
```

**演示：**

详细清看[数学公式](#数学公式)

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 超链接

**代码：**

```
ULR格式：

[Zang.帝樱的博客 (diyingisader.github.io)](https://diyingisader.github.io/zang_diying.github.io/)

图片格式：

[![我的博客](https://avatars.githubusercontent.com/u/125773452?s=400&u=57a6081544c4c722f215e6f8fad54a4cc8cc82b4&v=4)](https://diyingisader.github.io/zang_diying.github.io/)
```

**演示：**

ULR格式：

[Zang.帝樱的博客 (diyingisader.github.io)](https://diyingisader.github.io/zang_diying.github.io/)

图片格式：

[![我的博客](https://avatars.githubusercontent.com/u/125773452?s=400&u=57a6081544c4c722f215e6f8fad54a4cc8cc82b4&v=4)](https://diyingisader.github.io/zang_diying.github.io/)

> **使用方法：** <br>ULR格式：`[名称](网站链接)`<br>图片格式：`[![名称](图片链接)](网站链接)`

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

### 字体样式

*斜体*

**加粗**

<u>下划线</u>

表情：:smile:

下上标：H~2~O、X^2^

高亮：== 高亮文字==

#### [返回 · Markdown基本语法 · 目录](#Markdown基本语法)

---

## Issues代码

### 图片对齐

**代码：**

```
<div align=center>
<img src="https://avatars.githubusercontent.com/u/125773452?s=400&u=57a6081544c4c722f215e6f8fad54a4cc8cc82b4&v=4" 
width="100" height="100">
</div>
```

**演示：**

<div align=center>
<img src="https://avatars.githubusercontent.com/u/125773452?s=400&u=57a6081544c4c722f215e6f8fad54a4cc8cc82b4&v=4" 
width="100" height="100">
</div>

**使用说明：**<br>
>` <div align=center>`（center=中间、left=左边、right=右边）<br>
>` <img src="https://avatars.githubusercontent.com/u/125773452?s=400&u=57a6081544c4c722f215e6f8fad54a4cc8cc82b4&v=4" `（将双引号内的链接更替为你的图片链接，图片链接可以在网页中直接复制）<br>
> `width="100" height="100">`（这窜代码可以更改图片的尺寸大小，width=宽、height=高）<br>
> `</div>`（结尾）

#### [返回 · Issues代码 · 目录](#Issues代码)

---

### 文本对齐

**代码：**

```
<div align=center>
文本
</div>
```

**演示：**

<div align=center>
文本
</div>

**使用说明：**<br>
> `<div align=center>`（center=中间、left=左边、right=右边）<br>
>` 文本`（此处可任意输入）<br>
> `</div>`（结尾）

#### [返回 · Issues代码 · 目录](#Issues代码)

---

### 添加B站视频

**代码：**

```
Gmeek-html<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=替换&bvid=替换&cid=替换&p=1&autoplay=0" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="100%" height="460px"></iframe>
```

**演示：**

Gmeek-html<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=1604800941&bvid=BV1qm421M7Xs&cid=1557311907&p=1&autoplay=0" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="100%" height="460px"></iframe>

> 提示：此代码不会在预览模式启用，上传至博客后即可见到效果。

**使用说明：**<br>
> 复制想要添加到博客的B站视频链接到，如下：<br>
> https://www.bilibili.com/video/BV17w4m1e7Lm/?spm_id_from=333.1007.tianma.1-1-1.click&vd_source=122727f6540d32e232b6b0645b9371cf <br>
> 然后在此网站解析链接：<br>
> https://www.ibilibili.com/ <br>
> 解析后复制：<br>
> AID: `1105874011`（在解析网站中复制）<br>
> CID: `1583942197` （在解析网站中复制）<br>
> Bvid: `BV17w4m1e7Lm`（在视频链接中复制<video/************/?spm_id_from>）<br>
> 将这些字符替换到源代码中即可<br>
> 提示：在Issues的编辑界面中只会显示源代码，将其上传后在博客中才能正常显示。

#### [返回 · Issues代码 · 目录](#Issues代码)

---

### 强调关键信息

**代码：**

```
> [!NOTE]
> #蓝色 注意 用户应该知道的有用信息，即使在浏览内容时也是如此。

> [!TIP]
> #绿色 提示 有助于将事情做得更好或更轻松的有用建议。

> [!IMPORTANT]
> #紫色 重要 用户需要了解的关键信息才能实现其目标。

> [!WARNING]
> #黄色 警告 需要用户立即关注以避免出现问题的紧急信息。

> [!CAUTION]
> #红色 谨慎 就某些行动的风险或负面结果提供建议。
```

**演示：**

> [!NOTE]
> #蓝色 注意 用户应该知道的有用信息，即使在浏览内容时也是如此。

> [!TIP]
> #绿色 提示 有助于将事情做得更好或更轻松的有用建议。

> [!IMPORTANT]
> #紫色 重要 用户需要了解的关键信息才能实现其目标。

> [!WARNING]
> #黄色 警告 需要用户立即关注以避免出现问题的紧急信息。

> [!CAUTION]
> #红色 谨慎 就某些行动的风险或负面结果提供建议。

**使用说明：**

> 五种含义的框，每种的首行代表的是对应的含义，次行可填写自定义内容。

#### [返回 · Issues代码 · 目录](#Issues代码)

---

### 自定义链接名称

**代码：**

```
[Github](https://github.com/)
```

**演示：**

[Github](https://github.com/)

**使用说明：**

> `[自定义名称](自定义超链接)`

#### [返回 · Issues代码 · 目录](#Issues代码)

---

### 下拉列表

**代码：**

```
<details>
    <summary>收纳</summary>
这是一段被收纳的文字。
    </details>
```

**演示：**

<details>
    <summary>收纳</summary>
这是一段被收纳的文字。
    </details>

**使用说明：**
> `<details>`<br>
> `  <summary>自定义名称</summary>`<br>
> `自定义文字`<br>
> `  </details>`（收纳结尾）

#### [返回 · Issues代码 · 目录](#Issues代码)

------

## config设置



### 在主页右上角添加外部链接

**代码：**

```
"singlePage":["about"],
"iconList":{"图标文本":"打开图标网站，选择一款16像素的图标复制SVG，然后将复制结果`<path d="代码"></path></svg>`中间的代码替换到此处即可},
"exlink":{"图标文本":"替换成自己的外部链接"},`
```

**使用说明：**

> 打开 `Code` 中的 `config.json`，然后将此代码复制到 ` "GMEEK_VERSION":"last"` 上面另起一行。<br>
> "singlePage":["about"],<br>
>
> "iconList":{"图标文本":"打开图标网站，选择一款16像素的图标复制SVG，然后将复制结果`<path d="代码"></path></svg>`中间的代码替换到此处即可},<br>
> "exlink":{"图标文本":"替换成自己的外部链接"},`<br>
> 
> 图标网站：[Octicons | Primer](https://primer.style/foundations/icons)<br>
> 复制结果样式:
> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M8 1.5a6.5 6.5 0 1 0 6.016 4.035.75.75 0 0 1 1.388-.57 8 8 0 1 1-4.37-4.37.75.75 0 1 1-.569 1.389A6.473 6.473 0 0 0 8 1.5Zm6.28.22a.75.75 0 0 1 0 1.06l-4.063 4.064a2.5 2.5 0 1 1-1.06-1.06L13.22 1.72a.75.75 0 0 1 1.06 0ZM7 8a1 1 0 1 0 2 0 1 1 0 0 0-2 0Z"></path></svg>

#### [返回 · config设置 · 目录](#config设置)
