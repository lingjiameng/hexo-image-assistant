# hexo-image-assistant
Hexo 图片助手。自动为 hexo 中的资源图片提供绝对路径。扩展的 markdown 语法支持轻松指定图片宽度，同时不影响正常的markdown阅读。

Hexo image assistant. Give asset image in hexo a absolutely path automatically. Extended markdown syntax supports easily specifying image width.

## 参考 Reference
> [hexo-asset-image](https://github.com/xcodebuild/hexo-asset-image)

> [hexo-asset-image-fixed](https://www.npmjs.com/package/hexo-asset-image-fixed)

> [Hexo中扩展Markdown语法设置图片的大小](https://bobcn.github.io/2018/03/24/hexo_reset_image_size/)

## 使用方法 Usage

```
npm install hexo-image-assistant --save
```

## 示例 Example

```shell
note
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
note.md
```
确保 `_config.yml` 中的 `post_asset_folder: true` 为真。

只需使用 `![logo](note/logo.jpg?400)` 即可插入 `logo.jpg` 并将宽度设置为 `400`。

---

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](note/logo.jpg?400)` to insert `logo.jpg` and set width to `400`.

## 历史 History

- 2024-07-20：扩展 markdown 语法支持指定图像宽度 by ljmeng
- 2019-04-07：修复标题包含 http/https 等关键字 by CoreJa
- 2018-04-18：支持 hexo-abbrlink by xcodebuild

---

- 2024-07-20: Extended markdown syntax supports specifying image width by ljmeng
- 2019-04-07: fix title contains a keyword like http/https  by CoreJa
- 2018-04-18: support hexo-abbrlink by xcodebuild