---
title: Hello Tainan
date: 2020-07-24 09:41:25
tags:
categories:
  - [Hello]
  - [Hexo]
  - [JavaScript]
---
## Hello Tainan, 就從這裡開始!

{% asset_img tainan.png "Hello Tainan" %}

##### Hello Tainan 程式碼

```javascript hello-tainan.js
const Hello = (name) => console.log(`Hello ${name}!`);

Hello('Tainan');
```

使用 Hexo [標籤外掛(Tag Plugins)](https://hexo.io/zh-tw/docs/tag-plugins)語法。

{% codeblock hello-tainan.js lang:javascript %}
const Hello = (name) => console.log(`Hello ${name}!`);

Hello('Tainan');
{% endcodeblock %}

{% codeblock line_number:false lang:bash %}
$ node hello-tainan
Hello Tainan!
{% endcodeblock %}

**Ok! 保持下去!**