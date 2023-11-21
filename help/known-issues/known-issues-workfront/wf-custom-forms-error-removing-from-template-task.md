---
title: 「自訂表單：無法在範本任務上大量新增或移除自訂表單」
description: 「如果使用者嘗試在範本任務上大量新增或移除自訂表單，則不會新增或移除表單，且使用者會看到錯誤。」
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '153'
ht-degree: 5%

---


# 自訂表單：無法在範本任務上大量新增或移除自訂表單

如果使用者嘗試在範本任務上大量新增或移除自訂表單，則未新增或移除表單，並且使用者會看到以下錯誤：

[!UICONTROL 請再試一次。無效引數： templateID值「XXXXXXXXXXXXXXXX」]

如果使用者使用指定的GUID找到範本，然後嘗試在其餘範本任務中新增或移除自訂表單，則使用其他templateID會再次發生錯誤。

可以在單一範本任務中新增或移除自訂表單。 此錯誤僅適用於大量新增或移除。

_於 2023 年 11 月 10 日首次回報。_
