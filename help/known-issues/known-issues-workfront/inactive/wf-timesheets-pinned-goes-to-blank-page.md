---
title: 「時程表：釘選的時程表移至空白頁面」
description: 「當使用者按一下Workfront中要移至其時程表的pin時，該pin會移至空白頁面。 此問題有解決辦法。」
hidefromtoc: true
feature: Timesheets
source-git-commit: 229d3accabec51a7c559279b680336ca096c0e70
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 4%

---


# 時程表：釘選的時程表移至空白頁面

當使用者按一下Workfront中要移至其時程表的pin時，該pin會移至空白頁面。

這是因為時程表的URL已變更。 此 `/own` url結尾的URL不再是正確的URL。 如果使用者已釘選包含的URL `/own`，該圖釘會導向到一個空白頁面。

**解決方法**

1. 取消釘選時程表。
1. 移除 `/own` 從URL結尾
1. 重新釘選時間表。

_首次回報於2024年5月7日。_

