---
home: true
heroImage: image/1.jpg
actionText: 快速上手 →
actionLink: /zh/guide/
features:
- title: 简洁至上
  details: 以 Markdown 为中心的项目结构，以最少的配置帮助你专注于写作。
- title: Vue驱动
  details: 享受 Vue + webpack 的开发体验，在 Markdown 中使用 Vue 组件，同时可以使用 Vue 来开发自定义主题。
- title: 高性能
  details: VuePress 为每个页面预渲染生成静态的 HTML，同时在页面被加载的时候，将作为 SPA 运行。
footer: MIT Licensed | Copyright © 2018-present Evan You
---
<!-- [[toc]] -->
# help
## base
*斜体* _斜体_

==>

> 引用外层
>> 嵌套引用
>>> 三层嵌套


**Bold** __Bold__ Bold

[link](https://github.com)

![Image](https://echarts.apache.org/zh/images/logo.png?_v_=20200710_1)
![Image](image/1.jpg)

>Blockquote  空格

| First Header  | Second Header | Third Header |
| :------------- | -------------: | ------------ |
| Content Cell  | Content Cell  |              |
| Content Cell  | Content Cell  |              |
| content       | Content Cell  | Content Cell |
| content       | Content Cell  | Content Cell |

* List1 * list
+ List2 - list
- List3 - list
    + 嵌套列表
    - 再嵌套列表

1. One
2. Two

---
***

`反引号` 会加上北京



```
六个反引号可写代码了
```
<details><summary>CLICK ME</summary>

<p>

#### We can hide anything, even code!

```javascript
   puts "Hello World"
```

</p>

</details>

# heading1
## heading2
`icon`
:cowboy_hat_face:

```md:no-v-pre
<!-- 这里会被 Vue 编译 md:no-v-pre-->
1 + 2 + 3 = {{ 1 + 2 + 3 }}
```

这是默认主题内置的 `<Badge />` 组件 <Badge text="演示" />