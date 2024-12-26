---
title: 校樣：不會產生 Webcapture 校樣
description: 當使用者嘗試建立 webcapture 校樣時，無法成功產生校樣。
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# 校樣：不會產生 Webcapture 校樣

>[!NOTE]
>
>此問題已結案，因為其目前按照設計運作。請參閱以下解決方法。

當使用者嘗試建立 webcapture 校樣時，無法成功產生校樣。

**解決方法**

此問題是因為某些 PDF 檔案的校樣產生時間過長所致。若要延長預設的 30 秒產生逾時，請在校訂管理員中於帳戶層級編輯「處理」設定的下列屬性：

`WebCaptureNavigationTimeout -> 120`

_於 2024 年 10 月 3 日首次回報。_
