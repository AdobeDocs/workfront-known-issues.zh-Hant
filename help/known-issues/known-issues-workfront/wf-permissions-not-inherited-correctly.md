---
title: 權限：物件權限未正確繼承
description: 繼承的權限未正確套用於物件。 這可能是由於繼承權限的複雜性所導致。
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# 權限：物件權限未正確繼承

>[!NOTE]
>
>產品團隊目前正在評估此問題的解決方案，這可能需要產品增強功能。 產品增強功能是在產品公告中而不是在維護更新中傳達。

繼承的權限未正確套用於物件。 這可能是由於繼承權限的複雜性所導致，而這些權限可能會受到以下因素的影響：

* 該物件與大量人員共享
* 大量物件受到繼承權限變更的影響

**解決方法**

限制物件的大小或複雜性可以幫助避免此問題。 我們建議任何父物件下的子物件數量不超過 10,000 個。

_於 2025 年 3 月 21 日首次回報。_
