---
title: 時程表：釘選的時程表會導向空白頁面
description: 當使用者在 Workfront 中按一下目的是轉至其時程表的圖釘時，該圖釘會轉到空白頁面。 此問題有解決方法。
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# 時程表：釘選的時程表會導向空白頁面

<!--article live for workaround-->

當使用者在 Workfront 中按一下目的是轉至其時程表的圖釘時，該圖釘會轉到空白頁面。

這是因為時程表的 URL 已變更。 URL 最後的 `/own` 不再是正確的 URL。 如果使用者釘選了包含 `/own` 的 URL，該圖釘會導致空白頁面。

**解決方法**

1. 取消釘選時程表。
1. 移除 URL 最後的 `/own`
1. 重新釘選時程表。

_於 2024 年 5 月 7 日首次通報。_
