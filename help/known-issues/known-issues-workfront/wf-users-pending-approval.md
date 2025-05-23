---
title: 使用者：新使用者上會顯示未決核准徽章
description: Workfront中的新使用者可能會顯示在具有待核准徽章的使用者清單中。 此徽章會持續存在超過數分鐘，並在頁面重新整理時仍然存在。
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---


# 使用者：新使用者上會顯示「未決核准」徽章

>[!NOTE]
>
>已移轉至Adobe Admin Console的組織中，可能會出現此問題。

Workfront中的新使用者可能會顯示在具有「待核准」徽章的使用者清單中。 此徽章會持續存在超過數分鐘，並在頁面重新整理時仍然存在。

當使用者大量上傳(例如從試算表或Workfront Kick-Start上傳)時，此問題會加劇。

預期的行為是徽章會在幾分鐘後消失，並在頁面重新整理時消失。

## 因應措施

當新增至Workfront的使用者未同步至Adobe Admin Console時，就會發生這種情況。

建議您採取下列因應措施：

### 解析個別使用者

您可以解析「使用者」清單中的個別使用者。

1. 在使用者清單中選取一個或多個使用者。
1. 按一下清單標題中的三點選單。
1. 選取&#x200B;**核准**。
1. 幾分鐘後，重新整理頁面。

### 解析新增至大量批次的使用者

若要解析大量新增的使用者，您可以直接將批次使用者新增到Adobe Admin Console。

如需指示，請參閱[管理多個使用者 | 在Adobe檔案中大量上傳CSV](https://helpx.adobe.com/enterprise/using/bulk-upload-users.html)。


_首次回報於2025年5月8日。_
