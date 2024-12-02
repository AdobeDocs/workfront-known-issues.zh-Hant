---
title: 版面配置範本：版面配置範本導致報告不一致
description: 傳統 Workfront 體驗中的版面範本在 Workfront 介面中不再可用，但仍可能影響 Workfront 資料。這可能會導致報告或儀表板上受版面範本 (例如共用對象) 影響的欄位出現不一致。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 875945978c7bdb4a7128ade826b6fbc31da04ae9
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 100%

---

# 版面範本：版面範本導致報告不一致

<!--Can delete after 9/24/2024-->

>[!NOTE]
>
>這個問題已解決。

傳統 [!DNL Workfront] 體驗中的版面範本在 [!DNL Workfront] 介面中不再可用，但仍可能影響 [!DNL Workfront] 資料。這可能會導致報告或儀表板上受版面範本 (例如[!UICONTROL 共用對象]) 影響的欄位出現不一致。

**解決方法**

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
