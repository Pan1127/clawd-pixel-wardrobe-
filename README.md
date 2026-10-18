# Clawd Pixel Wardrobe

一个纯前端的像素换装衣柜。可以自由组合服装、帽子、眼睛、腮红和饰品，搭配结果保存在浏览器 `localStorage`。

## 使用

直接打开 `index.html`，或在目录中运行任意静态文件服务器。项目没有后端、账号系统、接口密钥或第三方依赖。

## 添加新服装

1. 按 `302 × 300` 画布制作透明 SVG 图层。
2. 将素材放入 `assets/wardrobe/`。
3. 在 `index.html` 的 `SLOTS` 中登记素材；完整套装可同时登记进 `PRESETS`。

## 来源与致谢

本项目基于 [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) 的角色与像素宠物设计继续制作，感谢 [@rullerzhou-afk](https://github.com/rullerzhou-afk) 及原项目贡献者。

当前仓库将其中的换装部分整理为可独立运行的浏览器衣柜，并增加了服装图层、帽子、眼睛、腮红、饰品、套装预设和移动端横向选择界面。它不是原项目的官方版本，也不代表原作者或相关品牌的认可。

## 许可与素材权利

- 程序代码作为原项目的修改版本，依照 [GNU Affero General Public License v3.0](LICENSE) 发布。
- Clawd 角色及源自原项目的美术素材沿用原项目的权利说明。
- 本项目原创的衣服、帽子、表情、腮红和饰品允许二次修改，但必须保留署名和仓库链接，并以相同条款公开修改后的素材。
- 原创衣柜素材禁止收费、商用、付费分发，也禁止用于闭源或专有产品。完整条款见 [assets/LICENSE](assets/LICENSE)。
