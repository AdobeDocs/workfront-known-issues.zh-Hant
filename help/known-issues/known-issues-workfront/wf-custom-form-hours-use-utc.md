---
title: 「自訂表單：計算欄位中的 HOUR 函數使用 UTC」
description: 「當計算欄位包含 HOUR 函數，該函數根據 UTC 而不是預期時區傳回值。因此，任何基於 HOUR 值的計算都是不正確的。」
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 93%

---


# 自訂表單：計算欄位中的 [!UICONTROL HOUR] 函數使用 UTC

>[!NOTE]
>
>此問題已於2022年11月3日修正。

當計算欄位包含 [!UICONTROL HOUR] 函數，該函數根據 UTC 而不是預期時區傳回值。因此，任何基於 HOUR 值的計算都是不正確的。

_首次回報於 2022 年 10 月 17 日。_

