# ICO 制作工具

在浏览器里把 JPG、PNG 或 WEBP 做成可包含多个尺寸的 `.ico` 图标。全部处理都在本地完成，图片不会离开浏览器，也不会上传到任何服务器。

- 仓库：https://github.com/xueshaoyu/ico-maker
- 在线使用：https://xueshaoyu.github.io/ico-maker/

## 怎么用

1. 打开 [https://xueshaoyu.github.io/ico-maker/](https://xueshaoyu.github.io/ico-maker/)，或下载本仓库的 `index.html`，用浏览器直接打开。
2. 上传或拖入图片。页面已带一张示例图，可以先试一遍。
3. 勾选要写入同一个 `.ico` 的尺寸，需要时再添加 1–1024 的自定义边长。
4. 选择图片如何放进正方形，按需添加一个或多个背景色过滤，在棋盘格上确认预览。
5. 校验通过后下载 `.ico`。

## 功能

- 上传或拖入 JPG、PNG、WEBP
- 内置示例图
- 多选尺寸，并可添加 1–1024 的自定义整数边长
- 256×256 以上尺寸以 PNG 嵌入；ICO 目录字段只能记录为 256×256，兼容性取决于读取软件
- 适配方式：完整放入（contain）、居中裁切（cover）、拉伸（stretch）
- 可选多个背景色过滤：吸管取色、颜色选择器、独立容差
- 棋盘格预览透明区域
- ICO 校验
- 下载 `.ico`
- 图片只在浏览器内处理，不会离开本机

这是一个自包含的单页文件（`index.html`），无需安装或构建。
