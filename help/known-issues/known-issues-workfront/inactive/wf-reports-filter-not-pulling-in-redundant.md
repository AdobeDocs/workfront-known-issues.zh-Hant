---
title: 報告：報告篩選器未傳回預期結果
description: 報告中的篩選器可能不會傳回所有預期結果。 此問題有解決方法。
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '100'
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
