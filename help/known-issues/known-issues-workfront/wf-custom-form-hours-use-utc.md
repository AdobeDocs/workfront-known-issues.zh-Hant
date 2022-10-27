---
title: 「自訂表單：計算欄位中的HOUR函式使用UTC」
description: 「當計算欄位包含HOUR函式時，函式會根據UTC而非預期時區傳回值。 因此，任何基於HOUR值的計算都是不正確的。」
hidefromtoc: true
source-git-commit: 8f04dc85caf0019001913bb4762c924109516a96
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 4%

---


# 自訂表單： [!UICONTROL 小時] 函式使用UTC

>[!NOTE]
>
>此問題已於2022年10月27日修正。

當計算欄位包含 [!UICONTROL 小時] 函式，則函式會根據UTC而非預期時區傳回值。 因此，任何基於HOUR值的計算都不正確。

_首次回報於 2022 年 10 月 17 日。_

