---
title: '時程表：釘選的時程表會轉到空白頁'
description: 「當使用者在 Workfront 中按一下目的是轉至其時程表的圖釘時，該圖釘會轉到空白頁面。此問題有解決方法。」
hidefromtoc: true
feature: Timesheets
source-git-commit: 89eb14bfaccb517764af1711ca31e2926de63795
workflow-type: ht
source-wordcount: '123'
ht-degree: 100%

---


# 時程表：釘選的時程表會轉到空白頁

當使用者在 Workfront 中按一下目的是轉至其時程表的圖釘時，該圖釘會轉到空白頁面。

這是因為時程表的 URL 已變更。URL 最後的 `/own` 不再是正確的 URL。如果使用者釘選了包含 `/own` 的 URL，該圖釘會導致空白頁面。

**解決方法**

1. 取消釘選時程表。
1. 移除 URL 最後的 `/own` 
1. 重新釘選時程表。

_於 2024 年 5 月 7 日首次通報。_

