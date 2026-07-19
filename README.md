# ICC-CE 浮动栏主题市场

本仓库用于发布 Ink Canvas for Class 的浮动栏主题包。

本仓库提供市场索引文件 `themes.json`，客户端从 GitHub Raw 加载：

```text
https://raw.githubusercontent.com/InkCanvasForClass/ThemeMarket/main/themes.json
```

## 主题包格式

每个主题包为一个 `.icctheme` ZIP 文件，根目录必须包含：

```text
manifest.json
Theme.xaml
Assets/
```

主题资源键和开发说明请参考主题包中的 `manifest.json` 与 `Theme.xaml`。
