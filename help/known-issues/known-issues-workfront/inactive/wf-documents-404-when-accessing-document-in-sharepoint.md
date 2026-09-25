---
title: 檔案：存取從SharePoint連結的檔案時出現404錯誤
description: 當使用者嘗試存取透過 SharePoint 連結的文件時，被導向顯示 404 錯誤的頁面。
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# 文件：存取連結自 [!DNL SharePoint] 的文件時出現 404 錯誤

<!--Requested article. This issue is on the WF and WFP TOCs.-->

當使用者嘗試存取透過 [!DNL SharePoint] 連結的文件時，被導向顯示以下錯誤的頁面：

「[!UICONTROL 錯誤 404：找不到頁面。 此頁面無法使用。 請嘗試檢查 URL 或造訪不同頁面。]」

這是已知的 [!DNL SharePoint] 問題，當網站連結包含「@」符號時會發生此問題。

**解決方法**

[!DNL SharePoint] 建議產生簡短 URL，並將其用於連結。

_於 2023 年 3 月 14 日首次通報。_
