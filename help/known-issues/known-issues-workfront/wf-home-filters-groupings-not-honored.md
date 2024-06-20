---
title: 「新首頁：小工具篩選器和分組預設值沒有遵循版面配置範本」
description: 當使用者在新的首頁體驗中查看我的專案、我的任務或我的問題小工具時，該小工具的預設篩選器和分組並非指派給該使用者的版面配置範本中的預設設定。
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: ht
source-wordcount: '191'
ht-degree: 100%

---

# 新[!UICONTROL 首頁]：小工具篩選器和分組預設值沒有遵循版面配置範本

>[!NOTE]
>
>此問題已關閉，因為情況已如期運作。

當使用者在新的[!UICONTROL 首頁]體驗中查看[!UICONTROL 我的專案]、[!UICONTROL 我的任務]或[!UICONTROL 我的問題]小工具時，該小工具的預設篩選器和分組並非指派給該使用者的版面配置範本中的預設設定。

**因應措施**：

使用新首頁時，請務必記住使用者設定 (偏好設定) 的優先順序最高。因此，如果您使用版面配置範本為特定小工具設定預設篩選器或分組，其可能會因為現有使用者的偏好設定，而不會立即生效。若要套用新的篩選器或分組，您或使用者可能需要重設偏好設定。您可以將 `/resetUser` 附加到您的網址來重設偏好設定。

_於 2024 年 1 月 3 日首次通報。_
