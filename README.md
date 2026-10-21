<p align="center">
  <img src="assets/logo.svg" width="88" height="88" alt="Easy Utils logo">
</p>

<h1 align="center">Easy Utils · 图片工具箱</h1>

<p align="center">
  <b>49 个纯前端图片工具，全部在浏览器本地运行，图片不上传任何服务器。</b><br>
  <sub>49 browser-only image tools. Your images never leave your device.</sub>
</p>

<p align="center">
  <a href="https://easy-utils.com/tools/image-tools.html"><img alt="Online Demo" src="https://img.shields.io/badge/Online%20Demo-easy--utils.com-2d8cf0?style=flat-square"></a>
  <a href="https://easy-utils.com"><img alt="Website" src="https://img.shields.io/badge/Website-easy--utils.com-22c1c3?style=flat-square"></a>
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-52c41a?style=flat-square"></a>
  <a href="en/index.html"><img alt="English" src="https://img.shields.io/badge/Docs-English-8b5cf6?style=flat-square"></a>
</p>

---

## 关于这个项目

这是 [Easy Utils](https://easy-utils.com) 图片工具分类的**开源版本**。官方在线版在 [https://easy-utils.com/tools/image-tools.html](https://easy-utils.com/tools/image-tools.html)，本仓库则是同一套代码的可独立部署版本：不依赖任何后端，克隆下来就能跑，也可以整目录部署到你自己的域名。

做这个仓库的初衷很简单：图片处理这类操作本来就不需要服务器。把代码开放出来，一方面方便开发者二次开发，另一方面也让"图片不上传"这件事变得可以被验证——你可以自己读一遍代码，确认没有网络请求把图片传走。

## 特性

- **纯前端，零后端**：所有转换、压缩、裁剪都在 Canvas / WebAssembly 里完成，没有服务器接口，也没有上传环节。
- **隐私可验证**：图片始终留在你的设备上。断网后除第三方库首次加载外，全部功能照常可用。
- **中英双语**：根目录为简体中文，`en/` 为英文，两边共用同一套 JS 内核。
- **零构建**：没有 npm、没有打包步骤，直接打开 HTML 就能跑，改完刷新即可。
- **开源免费**：MIT 许可，可自由用于个人或商业项目，也可自部署到自己的域名。

## 在线演示

| 版本 | 地址 |
| --- | --- |
| 官方在线版（中文） | [https://easy-utils.com/tools/image-tools.html](https://easy-utils.com/tools/image-tools.html) |
| 官方在线版（英文） | [https://easy-utils.com/en/tools/image-tools.html](https://easy-utils.com/en/tools/image-tools.html) |
| 本仓库中文版 | `index.html` |
| 本仓库英文版 | `en/index.html` |

## 工具清单（49 个）

表格里的工具名指向 [Easy Utils](https://easy-utils.com) 的在线详情页（含使用说明与常见问题），第二列是本仓库对应的文件，方便直接定位源码。

| 工具 | 本地文件 | 说明 | 分类 |
| --- | --- | --- | --- |
| [图片格式转换](https://easy-utils.com/image-converter.html) | [`image-converter.html`](image-converter.html) | 支持JPG/PNG/WebP/HEIC/AVIF等多格式批量互转 | 格式转换 |
| [AVIF转JPG](https://easy-utils.com/avif-to-jpg.html) | [`avif-to-jpg.html`](avif-to-jpg.html) | 将AVIF图片转换为JPEG格式，保持高质量 | 格式转换 |
| [AVIF转PNG](https://easy-utils.com/avif-to-png.html) | [`avif-to-png.html`](avif-to-png.html) | 将AVIF图片转换为PNG格式，无损输出 | 格式转换 |
| [BMP转JPG](https://easy-utils.com/bmp-to-jpg.html) | [`bmp-to-jpg.html`](bmp-to-jpg.html) | 将BMP图片转换为JPG格式，大幅减小文件体积 | 格式转换 |
| [GIF转JPG](https://easy-utils.com/gif-to-jpg.html) | [`gif-to-jpg.html`](gif-to-jpg.html) | 将GIF图片转换为JPG格式，提取首帧画面 | 格式转换 |
| [GIF转WebP](https://easy-utils.com/gif-to-webp.html) | [`gif-to-webp.html`](gif-to-webp.html) | 将GIF图片转换为WebP格式，提取首帧画面 | 格式转换 |
| [JFIF转JPG](https://easy-utils.com/jfif-to-jpg.html) | [`jfif-to-jpg.html`](jfif-to-jpg.html) | 将JFIF格式转换为标准JPG格式 | 格式转换 |
| [JPG转GIF](https://easy-utils.com/jpg-to-gif.html) | [`jpg-to-gif.html`](jpg-to-gif.html) | 将JPG图片转换为GIF格式 | 格式转换 |
| [JPG转JFIF](https://easy-utils.com/jpg-to-jfif.html) | [`jpg-to-jfif.html`](jpg-to-jfif.html) | 将标准JPG转换为JFIF交换格式 | 格式转换 |
| [JPG转PNG](https://easy-utils.com/jpg-to-png.html) | [`jpg-to-png.html`](jpg-to-png.html) | 将JPG图片转换为PNG格式，支持透明背景 | 格式转换 |
| [JPEG转WebP](https://easy-utils.com/jpg-to-webp.html) | [`jpg-to-webp.html`](jpg-to-webp.html) | 将JPEG图片转换为WebP格式，支持高质量压缩 | 格式转换 |
| [PNG转JPG](https://easy-utils.com/png-to-jpg.html) | [`png-to-jpg.html`](png-to-jpg.html) | 将PNG图片转换为JPEG格式，减小文件大小 | 格式转换 |
| [PNG转WebP](https://easy-utils.com/png-to-webp.html) | [`png-to-webp.html`](png-to-webp.html) | 将PNG图片转换为WebP格式，大幅减小文件体积 | 格式转换 |
| [WebP转JPG](https://easy-utils.com/webp-to-jpg.html) | [`webp-to-jpg.html`](webp-to-jpg.html) | 将WebP图片转换为JPEG格式，兼容所有设备 | 格式转换 |
| [WebP转PNG](https://easy-utils.com/webp-to-png.html) | [`webp-to-png.html`](webp-to-png.html) | 将WebP图片转换为PNG格式，支持透明背景 | 格式转换 |
| [SVG转JPG](https://easy-utils.com/svg-to-jpg.html) | [`svg-to-jpg.html`](svg-to-jpg.html) | 将SVG矢量图转换为JPG位图格式 | 格式转换 |
| [SVG转PNG](https://easy-utils.com/svg-to-png.html) | [`svg-to-png.html`](svg-to-png.html) | 将SVG矢量图转换为PNG位图格式，支持透明背景 | 格式转换 |
| [ICO图标转换](https://easy-utils.com/ico-to-image.html) | [`ico-to-image.html`](ico-to-image.html) | 将图片转换为ICO格式，用于网站favicon图标 | 格式转换 |
| [图片Base64互转](https://easy-utils.com/image-base64-converter.html) | [`image-base64-converter.html`](image-base64-converter.html) | 将图片转换为Base64编码，或将Base64字符串解码为图片 | 格式转换 |
| [HEIC转PDF](https://easy-utils.com/heic-to-pdf.html) | [`heic-to-pdf.html`](heic-to-pdf.html) | 将iPhone苹果HEIC照片转换为PDF，支持批量处理 | 格式转换 |
| [JPG转PDF](https://easy-utils.com/jpg-to-pdf.html) | [`jpg-to-pdf.html`](jpg-to-pdf.html) | 将JPG图片转换为PDF文档，支持批量处理 | 格式转换 |
| [图片转PDF](https://easy-utils.com/images-to-pdf.html) | [`images-to-pdf.html`](images-to-pdf.html) | 多格式图片批量转PDF，支持拖拽排序和自定义设置 | 格式转换 |
| [PNG转PDF](https://easy-utils.com/png-to-pdf.html) | [`png-to-pdf.html`](png-to-pdf.html) | 将PNG图片转换为PDF文档，支持批量处理 | 格式转换 |
| [PDF转图片](https://easy-utils.com/pdf-to-image.html) | [`pdf-to-image.html`](pdf-to-image.html) | 将PDF文档转换为图片格式，支持批量转换 | 格式转换 |
| [视频转GIF](https://easy-utils.com/video-to-gif.html) | [`video-to-gif.html`](video-to-gif.html) | 将视频转换为GIF动图，支持自定义帧率、尺寸、循环次数 | 格式转换 |
| [JPG图片压缩](https://easy-utils.com/jpg-compress.html) | [`jpg-compress.html`](jpg-compress.html) | 在线压缩JPG图片，减小文件大小，保持清晰度 | 压缩优化 |
| [GIF免费无损压缩](https://easy-utils.com/gif-compress.html) | [`gif-compress.html`](gif-compress.html) | 在线免费无损压缩GIF动画图片，减小文件大小 | 压缩优化 |
| [限定体积压缩](https://easy-utils.com/target-size-compress.html) | [`target-size-compress.html`](target-size-compress.html) | 设置目标文件大小，智能压缩图片至指定体积，支持批量处理 | 压缩优化 |
| [图片批量缩放](https://easy-utils.com/image-resize.html) | [`image-resize.html`](image-resize.html) | 按比例或自定义尺寸缩放图片，支持批量处理和打包下载 | 编辑处理 |
| [图片自由裁剪器](https://easy-utils.com/image-cropper.html) | [`image-cropper.html`](image-cropper.html) | 自由拖拽裁剪框，支持自定义尺寸和预设比例，实时预览 | 编辑处理 |
| [图片旋转翻转](https://easy-utils.com/image-rotate-flip.html) | [`image-rotate-flip.html`](image-rotate-flip.html) | 在线旋转和翻转图片，支持90°/180°/270°旋转和水平/垂直翻转 | 编辑处理 |
| [圆角图片生成器](https://easy-utils.com/round-corner-image.html) | [`round-corner-image.html`](round-corner-image.html) | 在线生成圆角图片，自定义圆角角度 | 编辑处理 |
| [图片边框阴影](https://easy-utils.com/image-border-shadow.html) | [`image-border-shadow.html`](image-border-shadow.html) | 自定义边框宽度、颜色、样式、圆角，添加阴影效果 | 编辑处理 |
| [图片调色面板](https://easy-utils.com/image-color-adjust.html) | [`image-color-adjust.html`](image-color-adjust.html) | 调整亮度、对比度、饱和度、色相、阴影、高光、锐化、模糊等参数 | 编辑处理 |
| [多图拼图合成](https://easy-utils.com/image-mosaic.html) | [`image-mosaic.html`](image-mosaic.html) | 支持水平、垂直、网格拼接方式，拖拽排序，自定义间距和背景色 | 编辑处理 |
| [图片马赛克模糊](https://easy-utils.com/image-mosaic-blur.html) | [`image-mosaic-blur.html`](image-mosaic-blur.html) | 拖拽选择区域，支持马赛克和高斯模糊两种方式，可撤销重置 | 编辑处理 |
| [图片九宫格分割](https://easy-utils.com/image-grid-splitter.html) | [`image-grid-splitter.html`](image-grid-splitter.html) | 自定义行列数，将图片分割成网格，支持打包下载 | 编辑处理 |
| [自定义形状裁剪](https://easy-utils.com/custom-shape-crop.html) | [`custom-shape-crop.html`](custom-shape-crop.html) | 选择圆形、心形、星形等形状裁剪图片，透明背景输出 | 编辑处理 |
| [图片加水印](https://easy-utils.com/image-watermark.html) | [`image-watermark.html`](image-watermark.html) | 为图片添加文字水印、Logo水印、防盗水印，支持批量处理 | 编辑处理 |
| [照片转手绘素描](https://easy-utils.com/photo-sketch.html) | [`photo-sketch.html`](photo-sketch.html) | 多种滤镜效果：素描、手绘、铅笔画、水墨画、炭笔画、彩色素描 | 编辑处理 |
| [在线抠图](https://easy-utils.com/background-remover.html) | [`background-remover.html`](background-remover.html) | 一键去除图片纯色背景，导出透明PNG或换白底、蓝底、红底 | 编辑处理 |
| [寸照生成器](https://easy-utils.com/id-photo-generator.html) | [`id-photo-generator.html`](id-photo-generator.html) | 上传照片一键制作一寸、二寸、护照等标准证件照，支持换底色、按 KB 压缩与相纸拼版打印 | 编辑处理 |
| [图片DPI修改](https://easy-utils.com/image-dpi-changer.html) | [`image-dpi-changer.html`](image-dpi-changer.html) | 修改图片DPI值，预设72/96/150/200/300 DPI，计算打印尺寸 | 编辑处理 |
| [表情包制作](https://easy-utils.com/meme-maker.html) | [`meme-maker.html`](meme-maker.html) | 上传图片添加搞笑文字，自定义字体、颜色、描边、位置 | 生成与查看 |
| [自定义占位图生成](https://easy-utils.com/placeholder-generator.html) | [`placeholder-generator.html`](placeholder-generator.html) | 自定义尺寸、颜色、文字生成占位图，支持多种输出格式 | 生成与查看 |
| [EXIF查看清除](https://easy-utils.com/exif-viewer.html) | [`exif-viewer.html`](exif-viewer.html) | 查看图片EXIF信息，包括拍摄信息、GPS信息等，支持清除EXIF数据 | 生成与查看 |
| [图片取色器](https://easy-utils.com/image-color-picker.html) | [`image-color-picker.html`](image-color-picker.html) | 点击图片获取颜色值，支持HEX、RGB、RGBA格式，生成配色方案 | 生成与查看 |
| [GIF动图编辑](https://easy-utils.com/gif-editor.html) | [`gif-editor.html`](gif-editor.html) | 编辑GIF动图，支持帧操作、文字添加、速度调整、重新合成 | 生成与查看 |
| [GIF逐帧拆分](https://easy-utils.com/gif-frame-extractor.html) | [`gif-frame-extractor.html`](gif-frame-extractor.html) | 将GIF动图分解为单帧图片，支持预览和批量下载 | 生成与查看 |

## 目录结构

```
.
├── index.html              中文工具集首页
├── <tool>.html             中文工具页（49 个）
├── en/
│   ├── index.html          英文工具集首页
│   └── <tool>.html         英文工具页（49 个）
├── assets/
│   ├── style.css           全站基础样式
│   ├── site.js             顶栏 / 页脚 / 回到顶部（站点外壳）
│   ├── tools-data.js       工具元数据（由构建脚本生成）
│   ├── en-i18n.js          英文页的运行时文案翻译
│   ├── logo.svg            项目 Logo
│   ├── <tool>.js           各工具的逻辑（中英共用）
│   └── <tool>.css          个别工具的补充样式
├── README.md
├── LICENSE
├── TRADEMARK.md
└── .nojekyll
```

## 本地运行

不需要安装任何依赖，任选一种方式：

```bash
# 方式一：Python 自带静态服务器
python -m http.server 8000

# 方式二：Node
npx serve .
```

然后打开 <http://localhost:8000>。

> 直接双击 `index.html` 也能打开，但浏览器对 `file://` 下的部分 API（如 Canvas 导出、剪贴板）有限制，建议用上面的本地服务器。

## 部署到 GitHub Pages

1. 把本目录推到 GitHub 仓库（默认分支 `main`）。
2. 仓库 **Settings → Pages**，Source 选 `Deploy from a branch`，分支选 `main`、目录选 `/ (root)`。
3. 等一两分钟，访问 `https://<用户名>.github.io/<仓库名>/`。

所有路径都是相对路径，因此放在仓库根目录或子目录（项目页）都能正常工作，不需要改任何配置。

## 二次开发

**改品牌名**：编辑 `assets/site.js` 顶部的 `BRAND` 配置（按语言取 `易工具` / `Easy Utils`），各页面 `<title>` 里的品牌后缀也在同一处维护。

**显示仓库链接**：在 `assets/site.js` 顶部把 `GITHUB_URL` 填成你的仓库地址，顶栏和页脚会自动出现入口。

**调整顶栏下拉 / 页脚栏目**：同一个文件里的 `POPULAR` 与 `FOOTER_COLS` 两个数组，填工具 slug 即可。

**新增工具**：把页面放到根目录与 `en/` 下，逻辑文件放 `assets/`，然后在 `assets/tools-data.js` 的 `items` 里加一条（或改构建脚本里的 `GROUPS` 后重新生成）。

## 技术说明

- 不依赖任何前端框架，全部原生 JS + Canvas API。
- 第三方能力按需从 CDN 加载：`heic2any`（HEIC 解码）、`jszip`（批量打包下载）、`jspdf`（PDF 生成）、`exif-js`（EXIF 读取）、`gif.js` / `gifenc`（GIF 编码）。
- 图标使用 [Bootstrap Icons](https://icons.getbootstrap.com/)，同样走 CDN。
- 所有工具均为客户端处理，因此性能取决于设备；超大图片或超多文件时建议分批处理。

## 品牌与商标

代码采用 MIT 许可，但 **Easy Utils 的名称与 Logo 属于商标标识，不随代码许可一并授权**。你可以自由修改、分发、商用这份代码，也可以移除界面上的品牌元素；如果保留，请勿暗示你的衍生项目由 Easy Utils 官方维护或背书。详见 [TRADEMARK.md](TRADEMARK.md)。

## 许可证

代码以 [MIT](LICENSE) 许可发布。
