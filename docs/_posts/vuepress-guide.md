---
title: VuePress使用指南
date: 2025-03-27
---

## VuePress基本配置

1. 安装VuePress
```bash
npm install -D vuepress@next
```

2. 创建文档结构
```
docs/
  .vuepress/
    config.js
  _posts/
    your-post.md
```

3. 启动开发服务器
```bash
npx vuepress dev docs
```

## 主题定制

可以在.vuepress/config.js中配置主题：
```javascript
module.exports = {
  themeConfig: {
    // 你的配置
  }
}
