# 头像下载站 Avatar Gallery

GitHub Pages 托管的头像下载站。纯静态，无依赖。

## 添加新头像

1. 把图片放进 `avatars/`，命名为 `avatar-N.webp`（N 递增）
2. 编辑 `index.html` 里的 `AVATARS` 数组，加一行：文件名、显示名、宽高、大小
3. 提交推送后 Pages 自动更新

## 本地预览

```bash
python3 -m http.server 8080
```

访问 http://localhost:8080
