# yi-zhang-marketing.github.io

Personal academic website for Yi Zhang.

## 页面结构

- `index.html`：页面布局、导航、全局样式和 footer。
- `sections/about-me.js`：About Me 个人信息、教育经历、研究兴趣和联系方式。
- `sections/research.js`：Working Papers 内容、论文状态和 SSRN 链接。
- `images/personal/`：个人照片资源，例如 `Yi.png`。
- `images/papers/`：论文图片资源，例如 `Voice.png` 和 `Streaming.jpg`。

内容模块通过普通 `<script>` 引入，无需构建工具。网站可直接部署到 GitHub Pages，也可以直接打开 `index.html` 预览。

更新个人信息、研究成果或图片时，分别编辑对应的 `sections/` 文件，或将图片放入 `images/personal/` 和 `images/papers/` 后更新图片引用路径。
