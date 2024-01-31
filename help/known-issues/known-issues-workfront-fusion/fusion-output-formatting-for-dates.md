---
title: 「Workfront Fusion：輸出日期的格式」
description: 「當日期輸出為字串時，日期可以輸出為UTC或ISO字串。 這取決於對應面板中的邏輯。」
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion：輸出日期的格式

當日期輸出為字串時，日期可以輸出為UTC或ISO字串。 這取決於對應面板中的邏輯：

* 如果函式內的日期已聯結至字串，則字串將會輸出到 **UTC** 格式。
* 如果Date未聯結在函式中，則會輸出為 **ISO字串**.

客戶應使用 `toString` （針對ISO）或 `formatDate` 函式以確保輸出符合所需的格式。
