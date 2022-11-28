# 😶「防回退空白字体」a prevent fallback blank font

一个防止字体回退到系统默认字体的空白字体，可以让未匹配字型呈空白显示。

覆盖了常用中日韩英数字符号，遇到未匹配字符欢迎反馈 [#1](https://github.com/itorr/blank-font/issues/1)

 - 不支持 Emoji
 - 不支持盲文
 - 有大体正常的字符宽度

需要不占宽度的空白字体可以去看看 [adobe-blank](https://github.com/adobe-fonts/adobe-blank)

## 安装
```bash
npm i blank-font
```
```javascript
import 'blank-font'
```

或
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/blank-font@0.0.2/blank.font.css">
```

## 使用
```css
.have-font-el{
    font-family: '某个字型不全的自定义字体名', blank;
}
```

## 使用例
https://lab.magiconch.com/eva-title/

## GitHub
https://github.com/itorr/blank-font