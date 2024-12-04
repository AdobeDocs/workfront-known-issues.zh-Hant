---
title: Workfront：ZScaler 設定可能導致效能下降
description: ZScaler Web 服務預設使用 http/1.1，這可能導致 Workfront 效能下降。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: ht
source-wordcount: '81'
ht-degree: 100%

---

# Workfront：ZScaler 設定可能導致效能下降

>[!NOTE]
>
>這是 ZScaler 的問題，並不會由 Workfront 進行修正。

ZScaler Web 服務預設使用 `http/1.1`，這可能導致 Workfront 效能下降。

**解決方法**

將 ZScaler 軟體設定為使用 `http/2`。您無法在 Workfront 中進行此項設定。

您可以在 ZScaler 文件中找到有關 `http/2` 的資訊。

_於 2024 年 11 月 18 日首次回報。_
