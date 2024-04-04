---
title: '「Workfront Fusion: Workfrontモジュールからの応答が 200 の RuntimeError」'
description: Workfrontモジュールは、「RuntimeError [200]」応答を返すことができます。 200 は成功した応答を示すのに対し、エラーはリクエストが失敗したことを示します。
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: 50f79121e0b027c3f0283cd43d19c885dde8268b
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 78%

---

# Workfront Fusion：Workfront モジュールからの RuntimeError 200 応答

<!--

>[!NOTE]
>
>This issue was fixed on March 28, 2024.

-->

Workfront モジュールは、`RuntimeError [200]` 応答を返すことがあります。200 は成功した応答を示すのに対し、エラーはリクエストが失敗したことを示します。

これは、応答が非常に長い場合に発生する場合があります。データは Fusion に返されますが、Fusion では処理できません。

_最初に報告されたのは 2024年1月3日（PT）です。_
