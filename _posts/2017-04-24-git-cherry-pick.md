---
layout: post
title: git cherry-pick 一整段的 commit
published: true
---

簡單記錄下今天用到的小技巧。

有的時候會加入多個 git remote，比如說 fork 出的原始碼，想要套用 upstream 的 PR，但那個 PR 又還沒合併；或是維護兩份原始碼，但又有共通的改動。這時候可以用 cherry-pick 指令，套用一整段 commit 到程式碼基礎上。

commit 粒度切的越細越好，這樣在 cherry-pick 時才好掌握（或是方便其它 git 指令操作，比如 rebase 也是粒度很細的行為）。當然其它工作流程另計了，合併到 master 時也可以 squash 起來。題外話。

cherry-pick 的使用方法很簡單，後面加上 commit hash 就好了，如下：

```bash
git cherry-pick COMMIT_SHA1
```

也可以 cherry-pick 一整段的 commit：

```bash
git cherry-pick START_SHA1^..END_SHA1
```

多加了一個 `^` 是表示開始 SHA1 的前一個 commit。

假如噴了合併衝突（merge conflicts），那就手動解決完，再用 `git cherry-pick --continue` 繼續套用剩餘的 commit。或是想回到還沒 `cherry-pick` 的狀態，用 `git cherry-pick --abort`，忽略這次的 cherry-pick。

大 GUY 4 這樣
