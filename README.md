# keui

NO gulp!  NO SCSS!  NO CoffeeScript!  NO Grunt、Stylus、LESS....!!!!
没有封装！！

简单时尚快捷的构建工具

# 模块
一个文件夹代表一个模块，每个模块由 `html` `css` `js`文件组成。

# UI 模块
负责呈现界面的模块，例如 `Button` 模块

## Button

### html 文件

```html
<button>按钮</button>

<button class="error">按钮</button>

incloud('button.html')
```

### CSS 文件

```css
button { }

button.error { }

@import button
```

### Javascript 文件

```js
export.button

button.prototype.error

require('button')
```




