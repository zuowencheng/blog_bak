---
title: MarkDown使用简述
date: 2017-12-31 11:18:07
tags:
- MarkDown
- guide
categories: Study-MarkDown
---

# 一、如何排版章节
```
大标题
===

小标题
---

#一级标题
## 二级标题
### 三级标题
```
# 二、如何插入列表
```
- AAAA
    + BBB
    + CCC
        * DDD
        * EEE
```
>- AAAA
>   + BBB
>   + CCC
>        * DDD
>        * EEE

# 三、如何插入超链接
`[www.baidu.com](www.baidu.com)`
[www.baidu.com](www.baidu.com)


# 四、如何引用别人的文字 
`-- 引用自《[立功主义](www.baidu.com)》`
-- 引用自《[立功主义](www.baidu.com)》
# 五、如何在行内修饰文字:删除、加粗、斜体、颜色
`**[专业主义](https://book.douban.com/subject/1790456/)**`
**[专业主义](https://book.douban.com/subject/1790456/)**

`- 描述：这本书着重阐释了真正的专家必须具备的四种能力：**先见能力**、**构思能力**、**讨论的能力**、**适应矛盾**的能力，以丰富的案例和深刻的洞见警示人们*重新思考专业*的内涵与效用，培养并吸纳专业人才。`
- 描述：这本书着重阐释了真正的专家必须具备的四种能力：**先见能力**、**构思能力**、**讨论的能力**、**适应矛盾**的能力，以丰富的案例和深刻的洞见警示人们*重新思考专业*的内涵与效用，培养并吸纳专业人才。

`- 状态：~~已读完。~~`
- 状态：~~已读完。~~

`- 备注： <span style="color:red">分析、设计、实现、改进</span>.`
- 备注： <span style="color:red">分析、设计、实现、改进</span>.

# 六、行内代码块
`html`

    这是一个代码块，此行左侧有四个不可见的空格。

# 七、如何插入代码：
```
#!/bin/bash
echo awawawawa | sed 's/w/W/g'

echo this is a test line | sed 's/\w+/[&]/g'
sed '/test/,/west/s/$/aaa bbb/' file
```
# 八、如何插入图片
<div align = left>`![事例图片](http://b.hiphotos.baidu.com/image/h%3D300/sign=0a54c9f99b45d688bc02b4a494c07dab/4b90f603738da977f0bb86e1b951f8198718e360.jpg)`</div>

![GitHub Mark](http://github.global.ssl.fastly.net/images/modules/logos_page/GitHub-Mark.png "GitHub Mark")


