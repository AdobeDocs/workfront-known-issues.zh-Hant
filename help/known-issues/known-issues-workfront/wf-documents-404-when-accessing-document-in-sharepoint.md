---
title: 「文檔：404存取從SharePoint連結的檔案時發生錯誤
description: 當使用者嘗試存取透過SharePoint連結的檔案時，系統會將他們帶往出現404錯誤的頁面。
hidefromtoc: true
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
source-git-commit: 17906db6aadc416c8be01e60d1b796143c97c061
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 73%

---

# 文件：存取連結自 [!DNL SharePoint] 的文件時出現 404 錯誤

<!--This issue is on the WF and WFP TOCs. By request.-->

當使用者嘗試存取透過 [!DNL SharePoint] 連結的文件時，被導向顯示以下錯誤的頁面：

「[!UICONTROL 錯誤 404：找不到頁面。此頁面無法使用。請嘗試檢查 URL 或造訪不同頁面。]」

這是已知的 [!DNL SharePoint] 問題，當網站連結包含「@」符號時會發生此問題。

**因應措施**

[!DNL SharePoint] 建議產生簡短 URL，並將其用於連結。

_於 2023 年 3 月 14 日首次通報。_
