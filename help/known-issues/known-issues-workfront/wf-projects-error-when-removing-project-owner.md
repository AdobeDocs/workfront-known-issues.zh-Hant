---
title: '''項目：從標題中刪除項目所有者時出錯'
description: 當用戶嘗試從項目標題中刪除項目所有者時，不會刪除項目所有者，並且用戶會看到錯誤消息。
hidefromtoc: true
exl-id: 3a995df4-5d6a-44e4-a644-997931c044bf
source-git-commit: 7570b2a560505d66e0e83656c9a601226998c11c
workflow-type: tm+mt
source-wordcount: '97'
ht-degree: 0%

---

# 專案：刪除 [!UICONTROL 專案擁有者] 從標題

>[!NOTE]
>
>此問題已於2022年9月9日修正。

當使用者嘗試移除 [!UICONTROL 專案擁有者] 在專案標題中， [!UICONTROL 專案擁有者] 未移除，且使用者會看見下列錯誤訊息：

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**因應措施**

移除[!UICONTROL  專案擁有者] 從項目 [!UICONTROL 詳細資料] 的上界。

_2022年8月9日首次報導。_
