---
title: "个人网站的搭建与基础配置"
description: "通过Spaceship和Cloudflare结合github来搭建属于你的网站！"
pubDate: "Mar 11 2025"
heroImage: "/blog-placeholder-1.jpg"
---

#### 在这篇博客中，你将学到：

- [通过Spaceship购买你的域名](https://blog.lcrstem.top/blog/create-website/#通过spaceship购买你的域名)
- [用Cloudflare托管你的域名](https://blog.lcrstem.top/blog/create-website/#用Cloudflare托管你的域名)
- 使用github来搭建属于你的网站
## 通过Spaceship购买你的域名
> **提示:** 如果你可以容忍诸如 *username.github.io* 这样的二级域名，你可以选择直接来到[使用github来搭建属于你的网站](https://blog.lcrstem.top/blog/create-website/#使用github来搭建属于你的网站)从而节省一笔不多的开销。但事实上，一个属于自己的域名能干的事还有很多，比如电子邮件转发，甚至解析你的MC服务器ip！

### 关于Spaceship

[Spaceship.com](https://www.spaceship.com/zh)是一家成立于 2019 年的域名注册商，其背后是全球第二大域名注册商和顶级网络服务提供商 [Namecheap](https://www.namecheap.com/)。Spaceship在安全性方面表现较为稳定，它采用了业内标准的SSL加密技术，确保用户在操作时的数据安全。并且Spaceship还提供域名隐私保护功能，帮助用户在注册域名时隐藏个人信息，防止恶意骚扰和隐私泄露。

### 为什么选择Spaceship

- Spaceship的域名种类齐全且价格实惠，可以满足不同行业和个人的需求
- Spaceship的用户界面友好，操作简单，能轻松完成购买流程
- Spaceship面向全球用户注册和管理域名，是一个国际化的平台，适合跨境业务的用户
- Spaceship是国外的域名商，使用Github等搭建网站无需国内备案（如果使用阿里云等的服务器还是要备案）
### 注册Spaceship账号
访问[Spaceship](https://www.spaceship.com/zh)，点击右上角的“登录”选项。点击登录页面左下角的“注册”并在如图所示的界面内按要求输入个人信息进行注册
![注册页面](/df892b8eebbc737de2ab5c88ab470597.png)
接着，根据提示完成邮箱验证等操作
![账户验证](/login.png)

### 配置您的账户
#### 选择后续支付方式
前往[付款方式](https://www.spaceship.com/zh/application/paymentmethod/)并选择您能使用的购买方式
目前支持的付款方式有：
- 支付宝
- PayPal
- Apple Pay
- Google Pay
- 信用卡/借记卡
- 比特币等加密货币
按操作要求完成付款验证
![地址簿](/pay.png)

### 添加地址簿
前往[地址簿式](https://www.spaceship.com/zh/application/address-book/)并点击添加地址
![地址簿](/add.png)
> **提示:** 这里并没有强制要求真实信息，如果您注重隐私，可以参考上图

### 搜素您的域名！
访问[域名搜索](https://www.spaceship.com/zh/domain-search/)并在搜索栏中输入您想要的域名如 *mywebsite.top* *mywebsite.xyz*等
具体关于域名类型可以访问[域名后缀](https://baike.sogou.com/m/fullLemma?lid=51153503)
在这里，我推荐.top，.xyz等域名后缀，这类域名首年通常仅需10元左右续费也是在30元左右，如图是 *lcrstemblog.top*的搜索结果，明显.top比别的域名便宜
![域名购买](/buyip.png)

若您决定了您要购买的域名，直接点击*加入购物车*并点击随后的*查看购物车*，在弹出的窗口中直接点击*继续*然后*结账*
网页将自动跳转至订单，**请仔细确认“支付详情”和“我的物品”的内容**，确认无误后点击结账，按照要求购买域名

至此，您的域名应该已经购买完毕了，你可以前往[域名管理](https://www.spaceship.com/zh/application/domain-list-application)来确认您的域名是否已经归您。并且您可以在此页面选择是否自动续费和手动续费
> **提示:** 当你的域名过期了，它将会被回收！请注意您域名的**到期时间**并通过自动续费或手动续费维持使用权！！
## 用Cloudflare托管你的域名

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
