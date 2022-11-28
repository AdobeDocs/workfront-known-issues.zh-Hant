---
title: 「Workfront聚變：無法建立與Google的連線"
description: "當使用者嘗試在任何Google連接器(例如Google表或Google磁碟)中建立連線時，不會建立連線，且使用者會看見各種錯誤訊息。"
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '103'
ht-degree: 3%

---


# [!DNL Workfront Fusion]:無法建立連接 [!DNL Google]

當使用者嘗試在 [!DNL Google] 連接器(例如 [!DNL Google Sheets] 或 [!DNL Google Drive])，則會看到開啟的視窗，並出現下列錯誤：

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

當用戶關閉此窗口時，連接失敗，內部出現以下錯誤 [!DNL Fusion]:

&quot;[!UICONTROL 錯誤：請求失敗，因為先前的請求失敗。 未指定訪問令牌。]&quot;

_於 2022 年 11 月 21 日首次通報。_

