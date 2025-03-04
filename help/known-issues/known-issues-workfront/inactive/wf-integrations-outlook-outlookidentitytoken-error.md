---
title: 整合：使用Workfront for Outlook時發生outlookIdentityToken錯誤
description: 當使用者使用Workfront for Outlook整合時，他們可能會看到錯誤。
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# 整合：使用Workfront for Outlook時發生outlookIdentityToken錯誤

當使用者使用Workfront for Outlook整合時，他們可能會看到以下錯誤：

```
Unexpected error
Unable to get the outlookIdentityToken
```

**因應措施**


若要解決此錯誤，您必須為組織啟用Microsoft 365舊版代號。 由於此工作必須在Microsoft 365中完成，Workfront無法為您的組織啟用這些代號。

如需啟用Microsoft 365舊版權杖的指示，請參閱Microsoft檔案中的[開啟或關閉舊版Exchange Online權杖](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)。

如需舊版權杖的詳細資訊，請參閱[我可以重新開啟Exchange Online舊版權杖嗎？Microsoft檔案中的](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on)。


_於2025年3月3日首次通報。_
