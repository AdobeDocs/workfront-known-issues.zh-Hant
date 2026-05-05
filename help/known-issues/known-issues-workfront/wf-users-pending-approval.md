---
title: 使用者：新使用者顯示待核准徽章
description: 在 Workfront 中，新的使用者可能會在使用者列表中顯示待核准徽章。 該徽章持續顯示超過幾分鐘，並且在頁面重新整理後仍然顯示。
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%

---

# 使用者：新使用者顯示「待核准」徽章

>[!NOTE]
>
>此問題可能出現在已遷移至 Adobe Admin Console 的組織中。

在 Workfront 中，新的使用者可能會在使用者列表中顯示「待核准」徽章。 該徽章持續顯示超過幾分鐘，並且在頁面重新整理後仍然顯示。

當使用者以大量批次上傳，例如從電子表格或 Workfront 快速啟動時，此問題會更加嚴重。

預期的行為是徽章會在幾分鐘後消失，並且在頁面重新整理後就不會再顯示。

## 替代解決方案

當新增的使用者未同步到 Adobe Admin Console 時，就會發生此問題。

我們建議以下替代解決方案：

### 解析個別使用者

您可以解析使用者清單中的個別使用者。

1. 在使用者清單中選取一個或多個使用者。
1. 按一下清單標頭中的三點選單。
1. 選取「**核准**」。
1. 幾分鐘後，重新整理頁面。

### 解析大批新增的使用者

若要解析大批新增的使用者，您可以直接將該批次的使用者新增至 Adobe Admin Console。

相關說明請參閱 Adobe 文件中的[管理多個使用者 | 上傳大量 CSV](https://helpx.adobe.com/tw/enterprise/using/bulk-upload-users.html)。


_於 2025 年 5 月 8 日首次回報。_
