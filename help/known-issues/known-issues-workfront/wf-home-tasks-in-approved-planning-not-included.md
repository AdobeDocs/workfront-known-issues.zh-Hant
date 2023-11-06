---
title: 「首頁：專案中狀態為「已核准」或「計畫」的任務未包含在「我的任務」或「首頁工作清單」中」
description: 「專案中狀態為「已核准」或「計畫」的任務不會顯示在「首頁」中。 有個因應措施。」
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 3%

---


# 首頁：專案中狀態為「已核准」或「計畫」的任務未包含在「我的任務」或「首頁工作清單」中

下列區域不會顯示狀態為「已核准」或「計畫」之專案中的任務：

* 傳統首頁：工作清單
* 新首頁：我的任務Widget

這是因為來自處於這些狀態的專案的任務目前包含在2000專案查詢限制中，但是它們未顯示在「我的任務」或「首頁工作清單」中。 這可能會造成使用者擁有少於2000個任務，這些任務不可見的情況。

**因應措施**

建立包含下列文字模式篩選器的自訂「工作總攬」報表：

當指定為AWAITING_ACCEPTION時，包含目前|已核准的專案：

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

接受指派時，包含目前|已核准|計畫專案：

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
