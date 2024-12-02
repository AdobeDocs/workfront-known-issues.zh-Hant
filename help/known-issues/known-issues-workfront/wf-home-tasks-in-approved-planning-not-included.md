---
title: 首頁：「已核准」或「規劃中」狀態的專案，其中任務未包含在「我的任務」或「首頁工作清單」
description: 「已核准」或「規劃中」狀態的專案，其中任務未包含在「首頁」。此問題有解決方法。
hidefromtoc: true
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 100%

---

# 首頁：「已核准」或「規劃中」狀態的專案，其中任務未包含在「我的任務」或「首頁工作清單」

>[!NOTE]
>
>產品團隊目前正在評估此問題的解決方案。解決此問題後，將在產品公告中進行溝通，而不是在維護更新中進行溝通。

「已核准」或「規劃中」狀態的專案，其中任務未顯示在以下區域：

* 傳統首頁：工作清單
* 新首頁：「我的任務」小工具

這是因為處於這些狀態的專案，其中任務目前包含在 2000 項查詢上限內，但它們不會顯示在「我的任務」或「首頁工作清單」中。這可能會造成這樣的情況：使用者的任務如果少於 2000 個，這些任務不會顯示。

**解決方法**

建立包含以下文字模式篩選器的自訂工作指派報告：

當工作指派為 AWAITING_ACCEPTANCE，包含目前|已核准專案：

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

當工作指派為 ACCEPTED，包含目前|已核准|規劃中專案：

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_於 2023 年 11 月 6 日首次回報。_
