---
title: 「Workfront Fusion：Workfront モジュールからの RuntimeError 200 応答」
description: Workfront モジュールは、「RuntimeError [200]」応答を返すことがあります。200 は成功した応答を示すのに対し、エラーはリクエストが失敗したことを示します。
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: e24d266002a913e5c6e2d5e40e9dad36deff541a
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 100%

---

# Workfront Fusion：Workfront モジュールからの RuntimeError 200 応答

>[!NOTE]
>
>この問題は、2024年5月9日（PT）に修正されました。

Workfront モジュールは、`RuntimeError [200]` 応答を返すことがあります。200 は成功した応答を示すのに対し、エラーはリクエストが失敗したことを示します。

これは、応答が非常に長い場合に発生する場合があります。データは Fusion に返されますが、Fusion では処理できません。

_最初に報告されたのは 2024年1月3日（PT）です。_
