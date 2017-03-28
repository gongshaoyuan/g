---
layout: post
title: browsersync 浏览器同步工具使用
category: 工作必备
tags: browsersync,浏览器同步
keywords: browsersync,浏览器同步
---

```c++

npm install -g browser-sync // 全局安装

npm install browser-sync --save-div // 安装到开发依赖

npm uninstall browser-sync -g // 全局删除


```

### 备注事项

通过package.json，可简化启动指令

```c++
npm start
```

```c++
{
  "private": true,
  "scripts": {
    "start": "node_modules/.bin/browser-sync start --server --files \"*.html,*.css,*.js\" "
  }
}
```






