---
title: 校樣：不會產生 Webcapture 校樣
description: 當使用者嘗試建立 webcapture 校樣，校樣並未成功產生。
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 59%

---

# 校樣：不會產生 Webcapture 校樣

>[!NOTE]
>
>此問題已關閉，因為目前已如期運作。請參閱下列因應措施。

當使用者嘗試建立 webcapture 校樣，校樣並未成功產生。

**解決方法**

此問題是因為特定PDF檔案的校訂產生時間過長所導致。 若要將產生逾時從預設的30秒增加，請在校訂管理員的帳戶層級的「處理設定」中編輯以下屬性：

`WebCaptureNavigationTimeout -> 120`

_於 2024 年 10 月 3 日首次回報。_
