---
title: 「Workfront:ZScaler 設定によってパフォーマンスが低下する可能性がある」
description: ZScaler の web サービスは、デフォルトで http/1.1 を使用しているので、Workfrontのパフォーマンスが低下する可能性があります。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---

# Workfront:ZScaler 設定によってパフォーマンスが低下する場合があります

>[!NOTE]
>
>これは ZScaler の問題であり、Workfrontでは修正されません。

ZScaler の web サービスは、デフォルトで `http/1.1` を使用しているので、Workfrontのパフォーマンスが低下する可能性があります。

**回避策**

`http/2` を使用するように ZScaler ソフトウェアを設定します。 これはWorkfrontでは設定できません。

`http/2` について詳しくは、ZScaler のドキュメントを参照してください。

_最初に報告されたのは 2024年11月18日（PT）です。_
