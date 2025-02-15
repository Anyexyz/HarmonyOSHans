# HarmonyOSHans

HarmonyOS-Hans 的切片文件，可以部署到 CDN 上，为站点添加 HarmonyOS 字体支持。

## 使用方法

### 引入字体

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Anyexyz/HarmonyOSHans@main/common.css">
```

或

```html
<link href="https://cdn.jsdelivr.net/npm/harmonyos-hans@1.0.0/common.min.css" rel="stylesheet">
```

或

```html
<link href="https://unpkg.com/harmonyos-hans@1.0.0/common.css" rel="stylesheet">
```

### 使用字体

根据需要在 CSS 中添加 `HuaweiFont-Regular` 字体，本例样式中已自适应字宽。

```html
<style>
  body {
    font-family: 'HuaweiFont-Regular', sans-serif;
  }
</style>
```