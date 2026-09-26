---
title: 自訂表單：跨物件自訂表單需要有「管理」或「編輯」存取權才能編輯欄位
description: 當用戶使用僅允許「管理」或「編輯」存取權的跨物件來建立表單，然後移除該物件類型時，自訂表單會繼續要求有管理或編輯存取權才能編輯欄位。 沒有欄位需要「管理」或「編輯」存取權的視覺化提示，且沒辦法重設表單。
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 92%
---
# 自訂表單：跨物件自訂表單需要有「[!UICONTROL 管理]」或「[!UICONTROL 編輯]」存取權才能編輯欄位

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>這個問題已解決

當用戶使用僅允許「[!UICONTROL 管理]」或「[!UICONTROL 編輯]」存取權的跨物件來建立表單，然後移除該物件類型時，自訂表單會繼續要求有「[!UICONTROL 管理]」或「[!UICONTROL 編輯]」存取權才能編輯欄位。 沒有欄位需要「管理」或「編輯」存取權的視覺化提示，且沒辦法重設表單。

**解決方法**

1. 新增分區符號至含有預設值 (若系統自動填入) 的表單。
2. 將分區符號移至表單上方。
3. 儲存表單。
4. 移除剛剛新增的分節符號並重新儲存表單。

_於 2022 年 11 月 9 日首次通報。_
