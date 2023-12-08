---
title: 「報告：匯出報告時出現 500 錯誤」
description: 當使用者嘗試匯出報告時，匯出失敗並出現 500 錯誤。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: ht
source-wordcount: '70'
ht-degree: 100%

---

# 報告：匯出報告時出現 500 錯誤

>[!NOTE]
>
>此問題已在 2023 年 11 月 30 日修正。

當使用者嘗試匯出報告時，匯出失敗並出現以下錯誤：

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

使用 `valueexpression` 來參考 `lastNote` 註釋文字的報告被回報出現此問題。

_於 2023 年 11 月 8 日首次回報。_
