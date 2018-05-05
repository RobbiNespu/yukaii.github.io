---
layout: post
title: 部落格 GitHub 新版型主題
comments: true
published: true
---

過程可以看 [PR#1](https://github.com/Yukaii/Blog/pull/1)，大致上是：

1. 引入 [primer css](https://primercss.io)
2. 清掉原本沒用到的 css
3. Post Layout 加上 `markdown-body` 的 class（[31360b](https://github.com/Yukaii/Blog/commit/31360b)）
4. 從 GitHub 上面拿 css 來用 XD

不囉嗦，直接上圖了。

## Before

![before-1](https://i.imgur.com/3rBAve0.png)

![before-2](https://i.imgur.com/bXb19SE.png)

## After

![after-1](https://i.imgur.com/McEpFdB.png)

![after-2](https://i.imgur.com/PqH6sup.png)

## Misc

另外附上最近弄的 VSCode Markdown Preview Theme。我習慣用暗色的 syntax highlight theme，但是 VSCode 的 Markdown Preview 會根據目前使用的 Theme，來使用亮色或暗色，所以我寫了一些覆蓋的 css，讓不論選亮色或是暗色主題都能使用明亮的 Markdown 預覽主題。與 [BigstickCarpet](https://gist.github.com/BigstickCarpet/) 的 GFM Theme 一起使用效果更佳 😁

[vscode-markdown-github-css](https://github.com/Yukaii/vscode-markdown-github-css)

![md1](https://i.imgur.com/hHbhwHJ.png)
