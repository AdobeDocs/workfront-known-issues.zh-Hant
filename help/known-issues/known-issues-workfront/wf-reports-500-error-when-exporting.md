---
title: 「報告：匯出報告時出現500錯誤」
description: 當使用者嘗試匯出報告時，匯出失敗並出現500錯誤。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 9%

---

# 報告：匯出報告時出現500錯誤

>[!NOTE]
>
>此問題已在 2023 年 11 月 30 日修正。

當使用者嘗試匯出報告時，匯出失敗並出現以下錯誤：

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

這已在使用 `valueexpression` 以參照 `lastNote` 附註文字。

_首次回報於2023年Novmeber 8。_
