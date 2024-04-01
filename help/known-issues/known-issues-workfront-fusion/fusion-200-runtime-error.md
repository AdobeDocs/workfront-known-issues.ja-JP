---
title: '「Workfront Fusion: Workfrontモジュールからの応答が 200 の RuntimeError」'
description: Workfrontモジュールは、「RuntimeError [200]」応答を返すことができます。 200 は成功した応答を示すのに対し、エラーはリクエストが失敗したことを示します。
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: 58d9dedba766417d68892c94d18d0ee4e9c03b51
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 80%

---

# Workfront Fusion：Workfront モジュールからの RuntimeError 200 応答

>[!NOTE]
>
>このイシューは 2024年3月28日（PT）に修正されました。

Workfront モジュールは、`RuntimeError [200]` 応答を返すことがあります。200 は成功した応答を示すのに対し、エラーはリクエストが失敗したことを示します。

これは、応答が非常に長い場合に発生する場合があります。データは Fusion に返されますが、Fusion では処理できません。

_最初に報告されたのは 2024年1月3日（PT）です。_
