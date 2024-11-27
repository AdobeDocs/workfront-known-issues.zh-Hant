---
title: 「Workfront：ZScaler設定可能會導致效能降低」
description: ZScaler的Web服務預設使用http/1.1，這可能會導致Workfront中的效能降低。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 1%

---

# Workfront： ZScaler設定可能會導致效能降低

>[!NOTE]
>
>這是ZScaler的問題，Workfront將不會修正。

ZScaler的Web服務預設使用`http/1.1`，這會導致Workfront中的效能降低。

**解決方法**

設定您的ZScaler軟體以使用`http/2`。 無法在Workfront中設定此專案。

您可以在ZScaler檔案中找到有關`http/2`的資訊。

_於2024年11月18日首次通報。_
