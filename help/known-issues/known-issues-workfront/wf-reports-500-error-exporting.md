---
title: 「報告：匯出報告時出現500錯誤」
description: 「當使用者嘗試匯出報告時，報告未匯出，並且使用者會看到一個錯誤。 此問題有解決辦法。」
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 0dbb29f11088b5c963f7972f3ec9e64ee55d6263
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 12%

---


# 報告：匯出報告時出現 500 錯誤

當使用者嘗試匯出報告時，報告未匯出，並且使用者會看到以下錯誤：

500：無法叫用「com.attask.biz.Parameter.getDisplayType()」，因為「parameter」為Null /attask/api-internal/report/export

當報告引用專案層級的自訂貨幣欄位時，就會發生這種情況。

**解決方法**

移除參考自訂貨幣欄位的欄，然後再次匯出報表。

_首次回報於2024年4月4日。_

