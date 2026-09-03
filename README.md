# Wen-Shuai Hu Homepage

这是一个基于 `https://wenshuaihu.github.io/` 当前公开页面内容重新实现的纯 HTML/CSS/JavaScript 学术主页模板。

## 文件

- `index.html`：页面结构和内容
- `styles.css`：响应式布局、导航、卡片、论文列表等样式
- `script.js`：移动端导航和页脚年份
- `README.md`：说明

## 本地运行

直接双击 `index.html` 即可查看；也可以在目录中运行：

```bash
python -m http.server 8000
```

然后打开 `http://localhost:8000/`。

## 部署到 GitHub Pages

把这几个文件放到 GitHub Pages 仓库根目录即可。入口文件是 `index.html`。

如果你的仓库是 `username.github.io`，发布后就是：

`https://username.github.io/`

## 下一步

如果需要做到“视觉 1:1”而不是目前这种结构与风格复刻，可以继续替换：
1. 原网站头像/图片资源；
2. 原站精确字体、颜色、边距和导航尺寸；
3. 每篇论文的 Website / Code / Slide 实际链接；
4. 原站的移动端折叠菜单和滚动状态。
