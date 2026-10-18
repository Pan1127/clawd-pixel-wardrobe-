# Clawd Pixel Wardrobe

一个纯前端的像素换装衣柜。可以自由组合服装、帽子、眼睛、腮红和饰品，搭配结果保存在浏览器 `localStorage`。

## 使用

直接打开 `index.html`，或在目录中运行任意静态文件服务器。项目没有后端、账号系统、接口密钥或第三方依赖。

## 添加新服装

1. 按 `302 × 300` 画布制作透明 SVG 图层。
2. 将素材放入 `assets/wardrobe/`。
3. 在 `index.html` 的 `SLOTS` 中登记素材；完整套装可同时登记进 `PRESETS`。

## 许可

代码与仓库中原创像素素材均以 MIT License 发布。
