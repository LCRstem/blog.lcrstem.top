---
title: "个人网站的搭建与基础配置"
description: "通过Spaceship和Cloudflare结合github来搭建属于你的网站！"
pubDate: "Mar 11 2025"
heroImage: "/blog-placeholder-1.jpg"
---

#### 在这篇博客中，你将学到：

- [通过Spaceship购买你的域名](https://blog.lcrstem.top/blog/create-website/#通过spaceship购买你的域名)
- 用Cloudflare托管你的域名
- 使用github来搭建属于你的网站
## 通过Spaceship购买你的域名
> **提示:** 如果你可以容忍诸如 *username.github.io* 这样的二级域名，你可以选择直接来到[使用github来搭建属于你的网站](https://blog.lcrstem.top/blog/create-website/#使用github来搭建属于你的网站)从而节省一笔不多的开销。但事实上，一个属于自己的域名能干的事还有很多，比如电子邮件转发，甚至解析你的MC服务器ip！

## 关于Spaceship

[Spaceship.com](https://www.spaceship.com/zh)是一家成立于 2019 年的域名注册商，其背后是全球第二大域名注册商和顶级网络服务提供商 [Namecheap](https://www.namecheap.com/)。Spaceship在安全性方面表现较为稳定，它采用了业内标准的SSL加密技术，确保用户在操作时的数据安全。并且Spaceship还提供域名隐私保护功能，帮助用户在注册域名时隐藏个人信息，防止恶意骚扰和隐私泄露。

# 为什么选择Spaceship

- Spaceship的域名种类齐全且价格实惠，可以满足不同行业和个人的需求
- Spaceship的用户界面友好，操作简单，能轻松完成购买流程
- Spaceship面向全球用户注册和管理域名，是一个国际化的平台，适合跨境业务的用户
- Spaceship是国外的域名商，使用Github等搭建网站无需国内备案（如果使用阿里云等的服务器还是要备案）
## 注册Spaceship账号
1.访问[Spaceship](https://www.spaceship.com/zh)，点击右上角的“登录”选项
2.点击登录页面左下角的“注册”并在如图所示的界面内按要求输入个人信息进行注册
![注册页面](/blog-placeholder-about.jpg)
```markdown
![Alt text](./full/or/relative/path/of/image)
```

### Output

![blog placeholder](/df892b8eebbc737de2ab5c88ab470597.png)

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

### Blockquote without attribution

#### Syntax

```markdown
> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  
> **Note** that you can use _Markdown syntax_ within a blockquote.
```

#### Output

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  
> **Note** that you can use _Markdown syntax_ within a blockquote.

### Blockquote with attribution

#### Syntax

```markdown
> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>
```

#### Output

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

### Syntax

```markdown
| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |
```

### Output

| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |

## Code Blocks

### Syntax

we can use 3 backticks ``` in new line and write snippet and close with 3 backticks on new line and to highlight language specific syntax, write one word of language name after first 3 backticks, for eg. html, javascript, css, markdown, typescript, txt, bash

````markdown
```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```
````

### Output

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

## List Types

### Ordered List

#### Syntax

```markdown
1. First item
2. Second item
3. Third item
```

#### Output

1. First item
2. Second item
3. Third item

### Unordered List

#### Syntax

```markdown
- List item
- Another item
- And another item
```

#### Output

- List item
- Another item
- And another item

### Nested list

#### Syntax

```markdown
- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese
```

#### Output

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Other Elements — abbr, sub, sup, kbd, mark

### Syntax

```markdown
<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
```

### Output

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
