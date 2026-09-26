---
title: 專案組合：使用者無法設定專案組合
description: 如果使用者沒有專案組合的存取權，就無法在專案上變更專案組合。
feature: Work Management
exl-id: 38ad277a-2087-486c-8715-93e275488697
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 100%
---
# 專案組合：使用者無法設定專案組合

>[!NOTE]
>
>此問題已結案，因為目前已如預期運作。

如果使用者沒有專案組合的存取權，就無法在專案上變更專案組合。

在以下情境中已回報此問題：

* 如果使用者無權存取專案指定的專案組合，則即使使用者嘗試移動專案時有權存取所要前往的專案組合，他們也無法視需要變更該專案組合。
* 嘗試使用專案範本建立專案時，如果建立專案的使用者無權存取該範本的專案組合或方案，建立的專案就不會包含這些指定的物件，且專案將顯示為獨立專案 (無專案組合或專案指定)。

**解決方法**

管理員可視需要授予存取權或進行調整。

_於 2024 年 6 月 26 日首次回報。_
