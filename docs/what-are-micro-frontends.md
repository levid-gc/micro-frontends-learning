---
id: what-are-micro-frontends
title: 什么是微服务？
sidebar_label: 什么是微服务？
slug: /
---

公司采用微服务架构的三个主要原因：

- **优化特性开发**：团队拥有开发特性所需的所有技能。独立的前端和后端团队之间不需要协调。
- **方便前端更新**：每个团队都拥有自己从数据库到前端的完整技术栈。团队独立地可以选择更新或者切换他们的前端技术。
- **提升客户关注**：每个团队可以直接向客户交付他们地特性，不需要纯粹地 API 团队或运维团队地存在。

## 整体概述

微前端并不是一个具体地技术，它是一种可选地组织和架构方式。

![img](../static/img/what-are-micro-frontends/figure-1.1.png)

### 系统和团队

A、B、C 团队三个盒子表示的就是垂直组织的软件系统。其中每个系统都是自治的，这就意味着即使相邻系统出问题后，它也能够提供服务。要想实现这种架构，每个系统都拥有它们自己的数据仓库。另外，对于其它系统的请求并不会依赖于同步请求。每个系统由一个团队管理，每个团队负责完整的从底至上的技术栈。

#### 团队使命

每个团队掌握其自身专业并能够向客户提供他们能够创造的价值。每个团队都应该有一个描述性的名称和清晰的使命，对于团队来说，清晰的使命是非常重要的，它会阐释团队的重心并且也是软件系统划分的基础。

#### 跨职能团队

微前端和其它架构最大的区别就是团队结构的不同。下图左侧，就是典型的 **专家团队**。人员是根据技能或者技术分组的。前端开发这被分到前端组；处理支付工作的专家被分到了支付服务组；业务和运维专家同样组成了他们自己的团队。采用微服务架构时团队结构通常是这样的。

![img](../static/img/what-are-micro-frontends/figure-1.3.png)

这种结构看起来并没有什么奇怪。前端开发者也喜欢一起工作，可以一起讨论 bug 的修复，技术的应用等，对于其他的团队同样也是这样。

这种假设其实并不完全合理。构建跨学科的团队越来越流行了，团队中有前后端工程师，还有运维和业务人员。由于不同的视角，这样的团队也更加具有创造力并且高效。

跨职能团队另一个好处就是所有的成员都直接参与特性的开发。在微服务模型中，服务和运维团队并不直接接触。他们从上级获取需求并且很多时候并不知道为什么这个需求很重要。而跨职能团队使得团队成员很容易全部参与进来并做贡献，最重要的是会获得 **产品的自我认同感**。

### 前端

### 前端集成

### 主题共享

## Markdown Syntax

To serve as an example page when styling markdown based Docusaurus sites.

## Headers

# H1 - Create the best documentation

## H2 - Create the best documentation

### H3 - Create the best documentation

#### H4 - Create the best documentation

##### H5 - Create the best documentation

###### H6 - Create the best documentation

---

## Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

---

## Lists

1. First ordered list item
1. Another item
   - Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
1. And another item.

* Unordered list can use asterisks

- Or minuses

+ Or pluses

---

## Links

[I'm an inline-style link](https://www.google.com/)

[I'm an inline-style link with title](https://www.google.com/ "Google's Homepage")

[I'm a reference-style link][arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. http://www.example.com/ or <http://www.example.com/> and sometimes example.com (but not on GitHub, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org/
[1]: http://slashdot.org/
[link text itself]: http://www.reddit.com/

---

## Images

Here's our logo (hover to see the title text):

Inline-style: ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png 'Logo Title Text 1')

Reference-style: ![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png 'Logo Title Text 2'

Images from any folder can be used by providing path to file. Path should be relative to markdown file.

![img](../static/img/logo.svg)

---

## Code

```javascript
var s = 'JavaScript syntax highlighting';
alert(s);
```

```python
s = "Python syntax highlighting"
print(s)
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

```js {2}
function highlightMe() {
  console.log('This line can be highlighted!');
}
```

---

## Tables

Colons can be used to align columns.

| Tables        |      Are      |   Cool |
| ------------- | :-----------: | -----: |
| col 3 is      | right-aligned | \$1600 |
| col 2 is      |   centered    |   \$12 |
| zebra stripes |   are neat    |    \$1 |

There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| _Still_  | `renders` | **nicely** |
| 1        | 2         | 3          |

---

## Blockquotes

> Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

---

## Inline HTML

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

---

## Line Breaks

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a _separate paragraph_.

This line is also a separate paragraph, but... This line is only separated by a single newline, so it's a separate line in the _same paragraph_.

---

## Admonitions

:::note

This is a note

:::

:::tip

This is a tip

:::

:::important

This is important

:::

:::caution

This is a caution

:::

:::warning

This is a warning

:::
