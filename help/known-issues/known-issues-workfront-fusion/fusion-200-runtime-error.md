---
title: 「Workfront Fusion：Workfront 模組發生 RuntimeError 並傳送 200 回應」
description: Workfront 模組可以傳回 `RuntimeError [200]` 回應。200 意味著回應成功，但錯誤顯示該要求並未成功。
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: e24d266002a913e5c6e2d5e40e9dad36deff541a
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 93%

---

# Workfront Fusion：Workfront 模組發生 RuntimeError 並傳送 200 回應

>[!NOTE]
>
>此問題已在2024年5月9日修正。

Workfront 模組可以傳回 `RuntimeError [200]` 回應。200 意味著回應成功，但錯誤顯示該要求並未成功。

如果回應非常長，則可能會發生此情況。資料回傳至 Fusion，但 Fusion 無法處理。

_於 2024 年 1 月 3 日首次通報。_
