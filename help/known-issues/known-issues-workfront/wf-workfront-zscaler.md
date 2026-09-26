---
title: Workfront：ZScaler 設定可能導致效能下降
description: ZScaler Web 服務預設使用 http/1.1，這可能導致 Workfront 效能下降。
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront：ZScaler 設定可能導致效能下降

>[!NOTE]
>
>這是 ZScaler 的問題，並不會由 Workfront 進行修正。

ZScaler Web 服務預設使用 `http/1.1`，這可能導致 Workfront 效能下降。

**解決方法**

將 ZScaler 軟體設定為使用 `http/2`。 您無法在 Workfront 中進行此項設定。

您可以在 ZScaler 文件中找到有關 `http/2` 的資訊。

_於 2024 年 11 月 18 日首次回報。_
