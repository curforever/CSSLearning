# CSS 小实验 · 调一调手感与像素

六个独立 HTML / CSS 练习，分别观察悬停、动画、开关、进度条、资料卡片与主题状态。保留可直接阅读的页面和样式，逐个理解效果怎样产生。

> Six small HTML/CSS experiments for hover, animation, controls and themes.

## 示例索引

| 示例 | 观察重点 | 页面 | 样式 |
| :--- | :--- | :--- | :--- |
| 悬停发光 | 悬停状态与光影反馈 | [demo1](demo1.html) | [style1](static/style1.css) |
| 动态水纹 | 伪元素与关键帧动画 | [demo2](demo2.html) | [style2](static/style2.css) |
| 发光开关 | 原生 checkbox 与选中状态 | [demo3](demo3.html) | [style3](static/style3.css) |
| 发光进度条 | 多条进度与动画表现 | [demo4](demo4.html) | [style4](static/style4.css) |
| 资料卡片 | 头像、信息层级与悬停展开 | [demo5](demo5.html) | [style5](static/style5.css) |
| 主题切换 | radio 状态与页面主题类 | [demo6](demo6.html) | [style6](static/style6.css) |

## 本地查看

在仓库根目录启动静态服务器：

```sh
python -m http.server 8000
```

打开 `http://localhost:8000/demo1.html`，把文件名换成 `demo2.html` 到 `demo6.html` 即可切换示例。页面使用相对资源路径，也可直接打开 HTML；图标使用外部 CDN，需要网络。

资料卡片与进度条的数值是样式示例，按钮用于展示样式，均不代表个人成果或完整业务功能。页面也支持键盘操作与减少动画的系统偏好。

[返回 GitHub 主页](https://github.com/curforever) · [机械键盘记录](https://github.com/curforever/Keyboard) · [交流与反馈](https://github.com/curforever/CSSLearning/issues)
