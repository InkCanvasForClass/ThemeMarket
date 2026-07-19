# ICC-CE 浮动栏主题市场

本仓库用于发布 Ink Canvas for Class 的浮动栏主题包。

推送到 `main` 后，GitHub Actions 会自动：

- 打包 `themes/` 下的主题为 `.icctheme`；
- 生成 `themes.json`；
- 计算 SHA256；
- 更新 `latest` Release。

主题市场索引地址：

```text
https://github.com/InkCanvasForClass/ThemeMarket/releases/download/latest/themes.json
```

## 主题包格式

每个主题包为一个 `.icctheme` ZIP 文件，根目录必须包含：

```text
manifest.json
Theme.xaml
Assets/
```
