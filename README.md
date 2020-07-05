# 轱辘 - 一个 Vue UI 组件

[![Build Status](https://www.travis-ci.org/unagi729/gulu-1.svg?branch=master)](https://www.travis-ci.org/unagi729/gulu-1)

## 介绍

这是我在学习 Vue 过程中做的一个 UI 框架，希望对你有用。

## 开始使用

1、添加 CSS 样式
    使用本框架前，请在 CSS 中开启 border-box

    ```
    *,*::before,*::after{box-sizing:border-box;}
    ```
    你还需要设置默认颜色等变量（后续会改为 SCSS 变量）
    ```
    :root {
    --button-height: 32px;
    --font-size: 14px;
    --button-bg: white;
    --button-active-bg: #eee;
    --border-radius: 4px;
    --color: #333;
    --border-color: #999;
    --border-color-hover: #666;
    }
    ```
    IE 15 及以上浏览器都支持此样式

2、安装 gulu
    ```
    npm i --save unagi-test-1-1
    ```
3、引入 gulu
    ```
    import { Button } from "unagi-test-1-1";
    import "unagi-test-1-1/dist/index.css";

    export default {
    name: "App",
    components: {
        "g-button": Button
    }
    };
    ```
    
## 文档

## 提问

## 变更记录

## 联系方式

## 贡献代码