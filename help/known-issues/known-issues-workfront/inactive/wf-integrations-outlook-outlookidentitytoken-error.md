---
title: 整合：使用 Workfront for Outlook 時出現 outlookIdentityToken 錯誤
description: 使用者使用 Workfront for Outlook 整合時，可能會看到錯誤。
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# 整合：使用 Workfront for Outlook 時出現 outlookIdentityToken 錯誤

>[!NOTE]
>
>適用於Outlook的Workfront整合已不再提供使用。 本文將於近期移除。

使用者使用 Workfront for Outlook 整合時，可能會看到以下錯誤：

```
Unexpected error
Unable to get the outlookIdentityToken
```

**解決方法**


若要解決此錯誤，您必須為組織啟用 Microsoft 365 舊版權杖。因為這必須在 Microsoft 365 中完成，所以 Workfront 無法為您的組織啟用這些權杖。

如需有關啟用 Microsoft 365 舊版權杖的說明，請參閱 Microsoft 文件中的[開啟或關閉舊版 Exchange Online 權杖](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)。

如需有關舊版權杖的詳細資訊，請參閱 Microsoft 文件中的[我可以重新開啟 Exchange Online 舊版權杖嗎？](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on)。


_2024、2025 年 3 月 3 日首次通報。_
