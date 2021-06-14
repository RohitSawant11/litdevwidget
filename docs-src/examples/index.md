---
layout: example.11ty.cjs
title: <go-widget> ⌲ Examples ⌲ Basic
tags: example
name: Basic
description: A basic example
---

<style>
  go-widget p {
    border: solid 1px blue;
    padding: 8px;
  }
</style>
<go-widget>
  <p>This is child content</p>
</go-widget>

<h3>CSS</h3>

```css
p {
  border: solid 1px blue;
  padding: 8px;
}
```

<h3>HTML</h3>

```html
<go-widget>
  <p>This is child content</p>
</go-widget>
```
