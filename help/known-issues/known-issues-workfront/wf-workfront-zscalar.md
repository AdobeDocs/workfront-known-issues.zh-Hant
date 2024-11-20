---
title: 「Workfront：ZScalar設定可能會導致效能降低」
description: 「ZScalar的Web服務預設使用http/1.1，這可能會導致Workfront的效能降低。」
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 1%

---


# Workfront： ZScalar設定可能會導致效能降低

>[!NOTE]
>
>這是ZScalar的問題，Workfront將不會修正。

ZScalar的Web服務預設使用`http/1.1`，這會導致Workfront中的效能降低。

**解決方法**

設定您的ZScalar軟體以使用`http/2`。 無法在Workfront中設定此專案。

您可以在ZScalar檔案中找到有關`http/2`的資訊。

_於2024年11月18日首次通報。_
