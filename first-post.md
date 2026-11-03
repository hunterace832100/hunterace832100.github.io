---
title: "示例文章：这个模板怎么用"
date: 2026-09-17T15:45:00+08:00
draft: false
math: true                      # ← 需要数学公式时设为 true，不需要可删掉这行
tags: ["示例", "AI工程"]
summary: "一篇可以直接照抄的模板文章，演示标题、代码、引用、图片和数学公式的写法。写自己的文章时把内容替换掉即可。"
ShowToc: true
---

> 这是一篇**模板/示例**文章。熟悉之后，把内容整篇替换成你自己的即可，或者直接删掉这个文件：
> `content/posts/first-post.md`。

## 一、正文和标题

正文直接用 Markdown 写。用 `##`、`###` 分级标题，页面右侧/顶部会自动生成目录（TOC）。

段落之间空一行即可。**加粗**、*斜体*、`行内代码`、[链接](https://gohugo.io/) 都是标准写法。

## 二、代码块

写语言名可以高亮，右上角自带一键复制按钮：

```python
def hello(name: str) -> str:
    """A tiny greeting."""
    return f"Hello, {name}!"


print(hello("world"))
```

## 三、引用与列表

> 引用块适合放结论或金句。

- 无序列表项
- 第二项
  1. 嵌套有序列表
  2. 第二步

## 四、图片

把图片放到 `static/images/` 下，然后这样引用（路径以 `/images/` 开头）：

```markdown
![图片说明](/images/example.png)
```

## 五、数学公式（KaTeX）

只要在**文件头**加上 `math: true`，就能写公式。行内公式用单个 `$` 包起来，例如 $e^{i\pi} + 1 = 0$；独立成行的公式用 `$$`：

$$
\text{Attention}(Q, K, V) = \text{softmax}\!\left(\frac{QK^\top}{\sqrt{d_k}}\right)V
$$

不需要公式的文章，把 `math: true` 删掉即可（默认不加载 KaTeX，页面更轻）。

---

就这些，开写吧 👇
