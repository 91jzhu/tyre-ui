# 快速上手

## 介绍

这是我在学习 Vue 时做的 UI 框架，希望对你有用

## 开始使用

1. 添加 CSS 样式

   使用本框架前，请CSS中开启 border-box

    ```
    *, *::before, *::after{ box-sizing: border-box; }
    ```
   IE 8 及以上浏览器都支持此样式
   你还需要设置默认颜色等变量
    ```
    html {
        $button-height: 32px;
        $font-size: 14px;
        $button-bg: white;
        $button-active-bg: #eee;
        $border-radius: 4px;
        $color: #333;
        $border-color: #999;
        $border-coloc-hover: #666;
    }
    ```
   IE 15 及以上浏览器都支持此样式



2. 引入tyre-ui
   ```
   import {Button,ButtonGroup,Icon} from 'tyre-ui'
   import 'tyre-ui/dist/index.css'
   
   export default {
       name: 'App',
       components: {
           't-button':Button,
           "t-icon":Icon
        }
   }
   ```

3. 引入 svg symbols
   ```
   <script src="//at.alicdn.com/t/font_2836712_oyveajskrej.js"></script>
   ```



