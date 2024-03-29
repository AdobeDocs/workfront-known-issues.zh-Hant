---
title: 「資源管理：由於職務角色問題導致財務計算不正確」
description: 「工時和財務計算可能不正確，即使在具有成本率的職務角色中記錄了工時，成本也顯示為 0。」
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: ht
source-wordcount: '141'
ht-degree: 100%

---


# 資源管理：由於職務角色問題導致財務計算不正確

>[!NOTE]
>
>此問題已於 2024 年 2 月 8 日修正。

工時和財務計算可能不正確，即使在具有成本率的職務角色中記錄了工時，成本也顯示為 0。

這是因為職務角色會自動建立沒有開始或結束日期的重複費率。由於沒有開始或結束日期，因此在執行財務計算時會將其值視為 0。

**解決方法**

1. 確認過去的正確資料已儲存。
1. 刪除沒有開始或結束日期的重複費率。
1. 重新計算財務。

_於 2023 年 1 月 18 日首次通報。_
