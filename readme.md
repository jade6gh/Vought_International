# 沃特国际-Vought International

### 哈哈好玩的要分享给大家

![图片](.\assets\images\image-1.png)





## 用法

* 此模板使用 Tailwind CSS，所有 Tailwind 类都带有 `tw-` 前缀，以便区分 Tailwind 类和其他类。

在开发过程中，将以下内容添加到 head 标签中：

```html
<link rel="stylesheet" href="tailwind-runtime.css"><!--replace with path to your tailwind runtime-->
```
在生产环境中使用：

```html
<link rel="stylesheet" href="tailwind-build.css"><!--replace with path to your tailwind build-->
```

要在开发过程中启动 Tailwind，请使用：
```html
npm run start:tailwind
```

要创建构建文件，请使用：
```html
npm run build:tailwind
```