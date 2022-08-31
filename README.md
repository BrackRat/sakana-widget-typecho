<p align="center">
<img src="https://raw.githubusercontent.com/dsrkafuu/sakana-widget/main/src/characters/chisato.png" height="160px">
<img src="https://raw.githubusercontent.com/dsrkafuu/sakana-widget/main/src/characters/takina.png" height="160px">
</p>

# Fix Details

修复 Typecho 下部分主题不能适配全局置顶的问题。

直接JS调用即可

https://cdn.jsdelivr.net/gh/brackrat/sakana-widget-typecho/sakana.min.js 

# 🐟「Sakana! Widget」

[English](https://github.com/dsrkafuu/sakana-widget/blob/main/README.md) | [简体中文](https://github.com/dsrkafuu/sakana-widget/blob/main/README.zh.md)

[![NPM](https://img.shields.io/npm/v/sakana-widget)](https://www.npmjs.com/package/sakana-widget)
[![License](https://img.shields.io/github/license/dsrkafuu/sakana-widget)](https://github.com/dsrkafuu/sakana-widget/blob/main/LICENSE)
![Upstream](https://img.shields.io/badge/upstream-3ad748a-blue)

<https://sakana.dsrkafuu.net>

Add the Sakana! Widget to your own web page! Support custom images, auto resizing and more runtime params!

## Usage

```html
<!-- https://cdn.jsdelivr.net/npm/sakana-widget@2.2.1/lib/sakana.min.js -->
<!-- https://cdnjs.cloudflare.com/ajax/libs/sakana-widget/2.2.1/sakana.min.js -->
<div id="sakana-widget"></div>
<script>
  function initSakanaWidget() {
    new SakanaWidget().mount('#sakana-widget');
  }
</script>
<script
  async
  onload="initSakanaWidget()"
  src="https://cdn.jsdelivr.net/gh/brackrat/sakana-widget-typecho/sakana.min.js"
></script>
```

