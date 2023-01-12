---
title: '''Workfront聚變：無法建立與Google的連線'
description: 當使用者嘗試在任何Google連接器(例如Google表或Google磁碟)中建立連線時，不會建立連線，且使用者會看見各種錯誤訊息。
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# [!DNL Workfront Fusion]：無法建立與 [!DNL Google] 的連線

>[!NOTE]
>
>此問題已於2023年1月9日修正。

當使用者嘗試在任何 [!DNL Google] 連接器 (例如 [!DNL Google Sheets] 或 [!DNL Google Drive]) 中建立連線時，他們會看到顯示以下錯誤的視窗：

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

當使用者關閉此視窗時，連線會失敗並在 [!DNL Fusion] 中出現以下錯誤：

「[!UICONTROL 錯誤：此要求失敗，因為先前的要求失敗。未指定存取權杖。]」

_於 2022 年 11 月 21 日首次通報。_
