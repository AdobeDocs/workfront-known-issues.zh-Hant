---
title: 「Workfront Fusion：Workfront 模組發生 RuntimeError 並傳送 200 回應」
description: Workfront 模組可以傳回 `RuntimeError [200]` 回應。200 意味著回應成功，但錯誤顯示該要求並未成功。
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: d88a785bb980ad4dcbb5ccb6b1b1bfb0cb61a161
workflow-type: ht
source-wordcount: '96'
ht-degree: 100%

---

# Workfront Fusion：Workfront 模組發生 RuntimeError 並傳送 200 回應

>[!NOTE]
>
>此問題已在 2024 年 7 月 25 日修正。

Workfront 模組可以傳回 `RuntimeError [200]` 回應。200 意味著回應成功，但錯誤顯示該要求並未成功。

如果回應非常長，則可能會發生此情況。資料回傳至 Fusion，但 Fusion 無法處理。

_於 2024 年 1 月 3 日首次回報。_
