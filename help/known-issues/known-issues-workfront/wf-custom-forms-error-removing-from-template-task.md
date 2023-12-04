---
title: 「自訂表單：無法在範本任務中大量新增或大量刪除自訂表單」
description: 如果使用者嘗試在範本任務中大量新增或大量刪除自訂表單，則不會新增或刪除表單，且使用者會看到錯誤。
hidefromtoc: true
feature: Custom Forms
exl-id: e9014f67-2098-46e4-a301-6a742a0c2ddb
source-git-commit: 45cea090d9e54514be9983b5443e7ee54b1f2d94
workflow-type: ht
source-wordcount: '153'
ht-degree: 100%

---

# 自訂表單：無法在範本任務中大量新增或大量刪除自訂表單

如果使用者嘗試在範本任務中大量新增或大量刪除自訂表單，則不會新增或刪除表單，且使用者會看到以下錯誤：

[!UICONTROL 請再試一次。無效參數：templateID 值「XXXXXXXXXXXXXXXX」]

如果使用者找到具有指定 GUID 的範本，然後嘗試在範本任務的其餘部分中新增或刪除自訂表單，則使用另一個 templateID 時將再次出現此錯誤。

可以在單一範本任務中新增或刪除自訂表單。僅大量新增或刪除時才會出現此錯誤。

_於 2023 年 11 月 10 日首次回報。_
