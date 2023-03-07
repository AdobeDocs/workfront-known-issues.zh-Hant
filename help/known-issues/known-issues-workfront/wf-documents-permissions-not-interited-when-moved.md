---
title: 「文件：當文件移至新專案時，不會繼承權限」
description: 「當使用者將文件移至不同專案時，該文件不會繼承新專案的共用權限。文件不會共用給共用專案的使用者。」
hidefromtoc: true
source-git-commit: 05592905aecebd7c6f99f4ffa7513630baae5692
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 57%

---


# 文件：當文件移至新專案時，不會繼承權限

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

當使用者將文件移至不同專案時，該文件不會繼承新專案的共用權限。文件不會共用給共用專案的使用者。

**因應措施：**

1. 導航到文檔的父對象，如「項目」、「任務」或「問題」。

1. 按一下繼承權限旁的「x」，然後按一下，從父對象的共用清單中移除繼承的權限 **[!UICONTROL 儲存]**.

1. 導覽回上層物件的共用清單，然後按一下「 」，以重新新增繼承的權限 **[!UICONTROL 還原]** 在繼承的權限旁，按一下 **[!UICONTROL 儲存]**.

或者，您也可以記下檔案的ID（可在「檔案詳細資訊」頁面的URL中找到），並聯絡Workfront客戶支援。

_於 2023 年 1 月 6 日首次通報。_

