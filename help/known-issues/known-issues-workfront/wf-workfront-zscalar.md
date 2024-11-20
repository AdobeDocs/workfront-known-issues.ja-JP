---
title: 「Workfront:ZScalar 設定によってパフォーマンスが低下する可能性がある」
description: 「ZScalar の web サービスは、デフォルトで http/1.1 を使用しているので、Workfrontのパフォーマンスが低下する可能性があります」
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront:ZScalar 設定を使用すると、パフォーマンスが低下する場合があります

>[!NOTE]
>
>これは ZScalar の問題であり、Workfrontでは修正されません。

ZScalar の web サービスでは、デフォルトで `http/1.1` を使用しているので、Workfrontのパフォーマンスが低下する可能性があります。

**回避策**

`http/2` を使用するように ZScalar ソフトウェアを設定します。 これはWorkfrontでは設定できません。

`http/2` について詳しくは、ZScalar のドキュメントを参照してください。

_最初に報告されたのは 2024年11月18日（PT）です。_
