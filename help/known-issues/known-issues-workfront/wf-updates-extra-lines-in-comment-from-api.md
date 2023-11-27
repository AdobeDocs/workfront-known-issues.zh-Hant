---
title: 「更新：透過 API 或 Workfront Fusion 發表的評論中出現額外的行」
description: 「當使用者透過 API 或 Workfront Fusion 提交評論時，「更新」區域顯示的評論會出現額外的行。有時有太多行，使用者必須向下捲動才能看到評論內容。」
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 6d87394383aaf54385163729f85ea065588967c9
workflow-type: ht
source-wordcount: '173'
ht-degree: 100%

---


# 更新：透過 API 或 [!DNL Workfront Fusion] 發表的評論中出現額外的行

>[!NOTE]
>
>此問題已在 2023 年 11 月 16 日修正。

當使用者透過 API 或 [!DNL Workfront Fusion] 提交評論時，「更新」區域顯示的評論會出現額外的行。有時有太多行，使用者必須向下捲動才能看到評論內容。

新的評論體驗有回報此問題。

**解決方法**

此問題是由評論中的 HTML 有空格或分行符號造成的。

為了避免此問題，請確保所有 HTML 都位於一行，HTML 元素之間沒有空格或分行符號。

若要查看受影響的評論不含額外的行，請切換到傳統評論體驗。

_於 2023 年 10 月 27 日首次回報。_
