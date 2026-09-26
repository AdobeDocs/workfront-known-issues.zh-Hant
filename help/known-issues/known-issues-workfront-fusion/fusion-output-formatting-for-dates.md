---
title: Workfront Fusion：日期的輸出格式
description: 在以字串輸出日期時，日期可以做為 UTC 或 ISO 字串輸出。 這取決於對應面板中的邏輯。
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion：日期的輸出格式

在以字串輸出日期時，日期可以做為 UTC 或 ISO 字串輸出。 這取決於對應面板內的邏輯：

* 如果函數中的日期與字串連結，則字串將以 **UTC** 格式輸出。
* 如果函數內的日期未有任何連結，則將輸出為 **ISO 字串**。

客戶應使用 `toString`(對於 ISO) 或 `formatDate` 函數以確保輸出的格式符合其需求。
