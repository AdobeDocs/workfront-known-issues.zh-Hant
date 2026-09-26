---
title: 核准：核准委派設定的天數不正確
description: 當使用者安排個人休假並委派他們對該時間的核准時，核准委派可能包括安排的休假之前或之後的天數。
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# 核准：核准委派設定的天數不正確

<!--Live for workaround-->

>[!NOTE]
>
>此問題已結案，因為這不是問題。

當使用者安排個人休假並委派他們對該時間的核准時，核准委派可能包括安排的休假之前或之後的天數。

**解決方法**

這種差異是由於使用者設定檔中的時區與使用者指派的時程表的時區之間的差異造成的。

我們建議為使用者工作的每個時區建立一個唯一的時程表，並將每個使用者指派到與其使用者設定檔中的時區相符的時程表。

_首次回報於 2022 年 3 月 24 日。_
