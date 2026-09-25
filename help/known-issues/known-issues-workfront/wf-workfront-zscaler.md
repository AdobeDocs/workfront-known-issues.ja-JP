---
title: Workfront：ZScaler 設定によりパフォーマンスが低下する場合がある
description: ZScalar の web サービスは、デフォルトで http/1.1 を使用するので、Workfront のパフォーマンスが低下する場合があります。
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront：ZScaler 設定によりパフォーマンスが低下する場合がある

>[!NOTE]
>
>これは ZScalar の問題であり、Workfront では修正されません。

ZScalar の web サービスは、デフォルトで `http/1.1` を使用するので、Workfront のパフォーマンスが低下する場合があります。

**回避策**

`http/2` を使用するように ZScalar ソフトウェアを設定します。 これは、Workfront では設定できません。

`http/2` について詳しくは、ZScalar のドキュメントを参照してください。

_最初に報告されたのは、2024年11月18日（PT）です。_
