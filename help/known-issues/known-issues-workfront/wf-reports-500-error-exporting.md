---
title: '報告：匯出報告時出現 500 錯誤'
description: 當使用者嘗試匯出報告時，報告並未匯出，且使用者會看到一個錯誤：此問題有解決方法。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: ht
source-wordcount: '105'
ht-degree: 100%

---

# 報告：匯出報告時出現 500 錯誤

>[!NOTE]
>
>此問題已在 2024 年 4 月 5 日修正。

當使用者嘗試匯出報告時，報告未匯出，且使用者會看到以下錯誤：

500：無法叫用「com.attask.biz.Parameter.getDisplayType()」，因為「parameter」為空值 /attask/api-internal/report/export

當報告引用項目層級自訂貨幣欄位時，會發生這種情況。

**解決方法**

刪除引用自訂貨幣欄位的欄並再次匯出報告。

_於 2024 年 4 月 4 日首次通報。_
