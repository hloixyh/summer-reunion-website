# 《夏日重逢》官方网站（角色布局更新版）

## 本次修改
- 保留原版首页、故事、画廊、游戏信息、开发日志和整体配色。
- 角色区改为交错双行：第一行左侧白九洲立绘、右侧简介；第二行左侧闲七灵简介、右侧立绘。
- 使用纵向原始立绘比例，`object-fit: contain`，避免横向裁切。
- 手机端自动改为纵向排列。
- 保留 Windows / Android 下载入口，并调整按钮样式。

## 文件结构
- `index.html`
- `style.css`
- `script.js`
- `assets/images/bai-jiuzhou.png`
- `assets/images/xian-qiling.png`

## 部署
将压缩包解压后，把其中的 `index.html`、`style.css`、`script.js`、`README.md` 和 `assets` 文件夹上传到 GitHub 仓库根目录，覆盖同名网页文件并新增图片资源。Netlify 会自动重新部署。

## 下载按钮说明
目前没有提供 Windows 安装包、Android APK 或正式下载地址，因此两个下载按钮仍显示“暂未开放下载”，不会指向不存在的文件。拿到正式文件并上传到可靠托管位置后，再将按钮链接替换为真实下载地址。

## 角色图片来源
- `bai-jiuzhou.png`：资料库中的 `b9z cf.png`
- `xian-qiling.png`：资料库中的 `xtm cn.png`
