---
title: 「報告：匯出報告時出現500錯誤」
description: 「當使用者嘗試匯出報告時，匯出會以500錯誤而失敗。」
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# 報告：匯出報告時出現500錯誤

當使用者嘗試匯出報告時，匯出失敗並出現以下錯誤：

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

這已在使用 `valueexpression` 以參照 `lastNote` 附註文字。

_首次回報於2023年Novmeber 8。_
