---
title: Workfront Fusion： Jira搜尋模組傳回錯誤
description: 舊版Jira聯結器使用的搜尋模組可能會導致錯誤。 此問題有因應措施
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 2%

---


# Workfront Fusion： Jira搜尋模組傳回錯誤

>[!NOTE]
>
>此問題是由於Jira在其產品中所做的變更所導致。

舊版Jira聯結器使用的搜尋模組可能會導致以下錯誤：

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

這是因為Jira端已棄用。

請注意：

* 只有搜尋模組會受到影響。 目前，Fusion聯結器使用的其他Jira API端點不會受到此淘汰的影響。

* 地理轉出可能會導致不一致。 Atlassian正在地區範圍內推出這項變更，這表示有些Jira Cloud執行個體可能仍會暫時支援較舊的端點。 這可能會導致環境間的行為不一致。

**解決方法**

如果您遇到此錯誤，您可以使用新聯結器的搜尋模組來取代舊版Jira聯結器的搜尋模組。 請注意，新的聯結器可讓您選取使用的API版本。 建立連線時，請務必在&#x200B;**API版本**&#x200B;欄位中選取&#x200B;**V3**。

_於2025年9月15日首次通報。_

