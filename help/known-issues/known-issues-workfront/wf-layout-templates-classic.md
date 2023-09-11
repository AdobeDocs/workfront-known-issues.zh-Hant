---
title: 「版面範本：版面範本導致報告不一致」
description: 「傳統 Workfront 體驗中的版面範本在 Workfront 介面中不再可用，但仍可能影響 Workfront 資料。 這可能會導致報告或儀表板上受版面範本 (例如共用對象) 影響的欄位出現不一致。」
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: ht
source-wordcount: '195'
ht-degree: 100%

---


# 版面範本：版面範本導致報告不一致

傳統 Workfront 體驗中的版面範本在 Workfront 介面中不再可用，但仍可能影響 Workfront 資料。 這可能會導致報告或儀表板上受版面範本 (例如共用對象) 影響的欄位出現不一致。

**因應措施**

使用 API 呼叫刪除傳統版面範本。 您必須先登入 Workfront。

>[!NOTE]
>
>全域和系統版面範本無法刪除。

1. 使用以下 API 呼叫找出要刪除的版面範本：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 記下要刪除之版面範本的 ID。
1. 使用以下 API 呼叫找出您的工作階段 ID：
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >切勿與任何人共用您的工作階段 ID。

1. 將版面範本 ID 和工作階段 ID 插入以下 API 呼叫中：
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 將步驟 4 中的 API 呼叫貼入瀏覽器的 URL 列，然後按 Enter 鍵。

   這將刪除版面範本。
