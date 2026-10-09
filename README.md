# Carrey Fan

Carrey 的个人主页与作品入口，使用原生 HTML、CSS 和 JavaScript 构建。

线上地址：[carreyf.space](https://www.carreyf.space/)

## 功能

- 全屏个人介绍与视频首屏
- 项目列表、网页缩略预览及折叠展开
- 经历、AI Coding 工具和写作内容
- X、抖音、邮箱与微信联系方式浮窗
- 音乐控制与底部奔马动画
- 响应式布局、键盘焦点和减少动态效果支持

## 本地运行

项目不需要构建工具。在项目目录启动一个静态服务器：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000/>。

## 第三方素材

第三方音乐、专辑封面和授权状态不明确的自定义字体不包含在公开仓库中。若你拥有相应授权，可自行添加：

- `audio/runaway-web.mp3`
- `icons/runaway-cover.jpg`
- `loading-culture-regular.ttf`

缺少这些文件不会影响主页主要内容，字体会自动使用后备字体，但音乐播放器将无法播放或显示专辑封面。

## 部署

这是一个静态网站，可直接部署到 Vercel、Cloudflare Pages、GitHub Pages 或其他静态托管服务。

## 许可

代码使用 [MIT License](LICENSE)。个人视频、照片、二维码、文章内容和第三方品牌素材不属于 MIT 授权范围，详见 [ASSET-LICENSE.md](ASSET-LICENSE.md)。
