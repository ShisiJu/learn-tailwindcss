# tailwindcss 初步了解

## 核心理念

### 功能类优先

[https://tailwindcss.com/docs/utility-first](https://tailwindcss.com/docs/utility-first)

### 复用样式

[https://tailwindcss.com/docs/reusing-styles](https://tailwindcss.com/docs/reusing-styles)

> 避免过早的抽取 CSS 类

## 安装与使用

```sh
# 版本 3.0.8
yarn add tailwindcss
```

tailwind.config.js 中配置代码路径

根据[tailwindcss 文档](https://tailwindcss.com/docs/installation)可以搜索预先定义好的功能类
在 src/case.html 中编写示例代码

```sh
# 打包: just-in-time 仅仅会打包preflight和用到的样式
npx tailwindcss -i ./src/tailwind.css -o ./dist/output.css
```

## 参考

- [CSS Utility Classes and "Separation of Concerns"](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/)
