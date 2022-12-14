---
title: 「自訂表單：如果欄位名稱包含雙引號或單引號，則不能在計算中使用欄位」
description: 「當使用者建立計算欄位運算式並嘗試納入名稱包含雙引號或單引號的預先輸入欄位時，系統將不接受計算，且使用者將看到訊息：此自訂運算式無效，請再試一次。」
hidefromtoc: true
source-git-commit: 254339d1baa9d8d7825e851aeafc9b27b1a1b669
workflow-type: ht
source-wordcount: '176'
ht-degree: 100%

---


# 「自訂表單：如果欄位名稱包含單引號或雙引號，則不能在計算中使用欄位」

>[!NOTE]
>
>產品團隊目前正在評估此問題的解決方案，這可能需要產品增強功能。產品增強功能是在產品公告中而不是在維護更新中傳達。

當使用者建立計算欄位運算式並嘗試納入名稱包含 `'` 或 `"` 的預先輸入欄位時，系統將不接受計算，且使用者將看到訊息：「[!UICONTROL 此自訂運算式無效，請再試一次。]」

此問題僅存在於預先輸入欄位中。名稱中包含 `'` 或 `"` 的文字欄位可以順利用於計算欄位運算式。

_於 2022 年 11 月 10 日首次通報。_

