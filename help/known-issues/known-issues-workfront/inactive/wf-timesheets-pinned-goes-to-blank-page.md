---
title: 「時程表：釘選的時程表移至空白頁面」
description: 當使用者按一下Workfront中要移至其時程表的pin時，該pin會移至空白頁面。 此問題有解決方法。
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 74%

---

# 時程表：釘選的時程表會轉到空白頁

<!--article live for workaround-->

當使用者在 Workfront 中按一下目的是轉至其時程表的圖釘時，該圖釘會轉到空白頁面。

這是因為時程表的 URL 已變更。URL 最後的 `/own` 不再是正確的 URL。如果使用者釘選了包含 `/own` 的 URL，該圖釘會導致空白頁面。

**解決方法**

1. 取消釘選時程表。
1. 移除 URL 最後的 `/own` 
1. 重新釘選時程表。

_於 2024 年 5 月 7 日首次通報。_
