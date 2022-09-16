---
title: '''プロジェクト：ヘッダーからプロジェクト所有者を削除中にエラーが発生しました'
description: ユーザーがプロジェクトのヘッダーからプロジェクト所有者を削除しようとしても、プロジェクト所有者は削除されず、ユーザーにエラーメッセージが表示されます。
hidefromtoc: true
exl-id: 3a995df4-5d6a-44e4-a644-997931c044bf
source-git-commit: 7570b2a560505d66e0e83656c9a601226998c11c
workflow-type: tm+mt
source-wordcount: '97'
ht-degree: 0%

---

# プロジェクト：次を削除中にエラーが発生しました： [!UICONTROL プロジェクト所有者] ヘッダーから

>[!NOTE]
>
>この問題は 2022 年 9 月 10 日に修正されました。

ユーザーが [!UICONTROL プロジェクト所有者] プロジェクトのヘッダーから、 [!UICONTROL プロジェクト所有者] が削除されず、ユーザーに次のエラーメッセージが表示されます。

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**回避策**

を削除します。[!UICONTROL  プロジェクト所有者] プロジェクトの [!UICONTROL 詳細] 領域

_最初のレポートは 2022 年 8 月 9 日です。_
