# 台球训练记录 Web App 发布说明

这个目录已经是可发布版本。上传整个 `billiards-training-app` 目录里的文件即可。

## 目录内容

- `index.html`：主页面
- `manifest.json`：PWA 安装信息
- `sw.js`：离线缓存脚本
- `icons/`：主屏幕图标

## 推荐使用方式

1. 把本目录上传到 GitHub Pages、Netlify、Cloudflare Pages 或其他静态网页托管。
2. 用 iPhone Safari 打开发布后的 HTTPS 网址。
3. Safari 底部点击“分享”。
4. 选择“添加到主屏幕”。
5. 以后从主屏幕图标打开即可。

## 注意

- 训练数据保存在手机 Safari 的 `localStorage` 中。
- 换手机、清除 Safari 网站数据、换浏览器后，原来的训练数据不会自动同步。
- 微信、QQ 等内置浏览器不建议作为正式使用入口。
