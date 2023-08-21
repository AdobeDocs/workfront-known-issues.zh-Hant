---
title: 「版面配置範本：版面配置範本造成報表不一致」
description: 「傳統Workfront體驗的版面範本在Workfront介面中不再提供，但仍可能影響Workfront資料。 這可能會導致報表或控制面板上受版面配置範本影響的欄位不一致（例如「共用對象」）。」
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---


# 版面配置範本：版面配置範本造成報表不一致

傳統Workfront體驗中的版面配置範本在Workfront介面中不再提供，但仍可能影響Workfront資料。 這可能會導致報表或儀表板上受版面配置範本影響的欄位不一致（例如「共用對象」）。

**因應措施**

使用API呼叫刪除傳統版面配置範本。 您必須登入Workfront。

>[!NOTE]
>
>無法刪除全域和系統配置範本。

1. 使用下列API呼叫，找出您要刪除的版面配置範本：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 記下要刪除的版面配置範本識別碼。
1. 使用下列API呼叫找出您的工作階段ID：
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >切勿與任何人共用您的工作階段ID。

1. 將版面配置範本ID和工作階段ID插入以下API呼叫：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 將步驟4的API呼叫貼到瀏覽器的URL列中，然後按Enter鍵。

   這將刪除版面配置範本。

