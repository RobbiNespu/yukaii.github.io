---
layout: post
title: 更改 Opera 的新分頁
date: 2018-06-06 09:57 +0800
---

我從去年起開始使用 Opera，原因有二：基於 Chromium 以及內建的暗色主題。不過這不是本篇的主題，就讓我輕輕帶過吧 XD

現在的 Opera 既然是基於 Chromium 改的，當然支援 Google Chrome 的瀏覽器擴充功能，只要安裝 Opera 官方出的 [Install Chrome Extensions](https://addons.opera.com/zh-tw/extensions/details/install-chrome-extensions/) 擴充套件，就能無縫直接在 Chrome Web Store 下載了，不過還是有些限制，比如 Chrome Apps 和主題就不支援，修改新分頁的擴充功能也沒辦法直接使用。

接下來教你怎麽啟用 Opera 修改新分頁的擴充功能 😝

1. 安裝完上面提到的 [Install Chrome Extensions](https://addons.opera.com/zh-tw/extensions/details/install-chrome-extensions/) 之後，到 [Chrome Web Store][new-tab-start-page-pro] 頁面安裝 New Tab Start Page Pro
2. 安裝修改新分頁的功能，以 [Unplash Instant](https://chrome.google.com/webstore/detail/unsplash-instant/pejkokffkapolfffcgbmdmhdelanoaih) 為例，一樣先到 Chrome Web Store 安裝
3. 複製擴充功能的 ID，在擴充功能 Web Store 網址的最後面，以 Unsplash Instant 為例，就是 `pejkokffkapolfffcgbmdmhdelanoaih`，也可以從 Opera 的擴充功能頁面拿到

    ![ID](https://i.imgur.com/MCcnznn.png)

4. 叫出 New Tab Start Page Pro 的設定頁，在 New Tab & Start Page URL 欄位填入：`chrome-extension://pejkokffkapolfffcgbmdmhdelanoaih/index.html`
5. 其它照截圖的選起來

    ![options](https://i.imgur.com/07NcIOh.png)

6. 按 Save 存檔

效果如下圖，雖然開啟新分頁之後會閃一下，聊勝於無啦

![gif](https://i.imgur.com/Ctvff8y.gif)

（完）

[new-tab-start-page-pro]: https://chrome.google.com/webstore/detail/new-tab-start-page-pro/mjfahldkpjhcnfbbmdhpjolcjpcfhcpj
