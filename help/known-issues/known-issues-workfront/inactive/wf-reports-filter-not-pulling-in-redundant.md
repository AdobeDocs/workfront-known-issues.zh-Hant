---
title: 「報告：報告篩選器未傳回預期結果」
description: 報告中的篩選器可能不會傳回所有預期結果。此問題有解決方法。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
source-git-commit: 9457b520c469c729f8727b1efd21bbde117b9546
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 100%

---

# 報告：報告篩選器未傳回預期結果

>[!NOTE]
>
>這個問題已結案。

報告中的篩選器可能不會傳回所有預期結果。

當篩選器設定為傳回具有特定條件的結果，並且包含會傳回相同條件子集之結果的 OR 規則時，可能會發生此狀況。

**解決方法**

確保篩選器的 OR 區塊不包含相同的評估條件。

_於 2024 年 3 月 11 日首次通報。_
