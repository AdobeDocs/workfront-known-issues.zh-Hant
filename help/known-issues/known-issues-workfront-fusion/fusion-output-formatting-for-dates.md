---
title: 「Workfront Fusion：輸出日期的格式」
description: 在以字串輸出日期時，日期可以做為 UTC 或 ISO 字串輸出。這取決於對應面板中的邏輯。
hidefromtoc: true
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 87%

---

# Workfront Fusion：日期的輸出格式

在以字串輸出日期時，日期可以做為 UTC 或 ISO 字串輸出。這取決於對應面板內的邏輯：

* 如果函數中的日期與字串連結，則字串將以 **UTC** 格式輸出。
* 如果函數內的日期未有任何連結，則將輸出為 **ISO 字串**。

客戶應使用 `toString`(對於 ISO) 或 `formatDate` 函數以確保輸出的格式符合其需求。
