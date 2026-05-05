---
title: Workfront Fusion：Jira 搜尋模組傳回錯誤
description: 舊版 Jira 連接器使用的搜尋模組可能會導致錯誤。 此問題有解決方法
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 100%

---

# Workfront Fusion：Jira 搜尋模組傳回錯誤

>[!NOTE]
>
>此問題是由於 Jira 在其產品中進行的更改所導致。

舊版 Jira 連接器使用的搜尋模組可能會導致以下錯誤：

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

這是由於 Jira 端的功能被淘汰所導致。

請注意：

* 只受搜尋模組影響。 目前，Fusion 連接器使用的其他 Jira API 端點不受此功能淘汰的影響。

* 地理區域推廣可能會導致不一致的情況。 Atlassian 正在區域性地推廣此更改，這意味著某些 Jira Cloud 執行個體可能仍會暫時支援舊的端點。 這可能會導致不同環境間的行為不一致。

**解決方法**

如果遇到此錯誤，您可以將舊版 Jira 連接器的搜尋模組替換為新版連接器的搜尋模組。 請注意，新版連接器允許您選擇使用的 API 版本。 建立連接時，請務必在 **API 版本**&#x200B;欄位中選擇 **V3**。

_於 2025 年 9 月 15 日首次回報。_
