---
title: 「新首頁：Widget篩選器和群組預設值未依配置範本執行」
description: 當使用者在新的首頁體驗中檢視我的專案、我的任務或我的問題Widget時，該Widget的預設篩選和分組不是指派給該使用者的版面配置範本中的預設設定。
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 36%

---

# 新[!UICONTROL 首頁]：小工具篩選器和分組預設值沒有遵循版面配置範本

>[!NOTE]
>
>此問題已關閉，因為情況已如期運作。

當使用者在新的[!UICONTROL 首頁]體驗中查看[!UICONTROL 我的專案]、[!UICONTROL 我的任務]或[!UICONTROL 我的問題]小工具時，該小工具的預設篩選器和分組並非指派給該使用者的版面配置範本中的預設設定。

**因應措施**：

使用新首頁時，請務必記住使用者設定（偏好設定）是優先順序。 因此，如果您使用版面配置範本為特定Widget設定預設篩選或分組，則由於現有使用者偏好設定，可能不會立即生效。 若要套用新的篩選器或群組，您或使用者可能需要重設偏好設定。 您可以透過附加來完成 `/resetUser` 至您的URL。

_於 2024 年 1 月 3 日首次通報。_
