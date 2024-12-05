---
title: 「Workfront：ZScaler 設定によりパフォーマンスが低下する場合がある」
description: ZScalar の web サービスは、デフォルトで http/1.1 を使用するので、Workfront のパフォーマンスが低下する場合があります。
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: ht
source-wordcount: '81'
ht-degree: 100%

---

# Workfront：ZScaler 設定によりパフォーマンスが低下する場合がある

>[!NOTE]
>
>これは ZScalar の問題であり、Workfront では修正されません。

ZScalar の web サービスは、デフォルトで `http/1.1` を使用するので、Workfront のパフォーマンスが低下する場合があります。

**回避策**

`http/2` を使用するように ZScalar ソフトウェアを設定します。これは、Workfront では設定できません。

`http/2` について詳しくは、ZScalar のドキュメントを参照してください。

_最初に報告されたのは 2024年11月18日（PT）です。_
