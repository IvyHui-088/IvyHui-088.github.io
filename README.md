# Ivy Hui — Product Manager × Design

个人作品集网站。单页静态站点：无构建步骤、无外部依赖、无 JavaScript 框架，一个 `index.html` 就是全部。

**线上地址**：https://ivyhui-088.github.io/

## 本地预览

在本文件夹下打开终端，运行：

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

然后浏览器访问 http://127.0.0.1:4173/ ，停止按 `Ctrl+C`。

不建议直接双击 `index.html` 打开——那样走的是 `file://` 协议，部分浏览器能力（字体、跨文件读取）会受限，和真正上线后的表现不一致。

## 目录

| 路径 | 内容 |
|---|---|
| `index.html` | 页面本体，样式与脚本全部内嵌 |
| `assets/` | 版块配图 |
| `images/` | 首页大图 |

## 更新发布

修改文件后推送即可，GitHub Pages 会自动重新构建（约 1 分钟）：

```bash
git add -A
git commit -m "改了哪里"
git push
```
