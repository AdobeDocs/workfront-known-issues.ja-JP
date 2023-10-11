---
title: 「レイアウトテンプレート：レイアウトテンプレートが原因でレポートに不整合が生じる」
description: 「Classic Workfront エクスペリエンスのレイアウトテンプレートは、Workfront インターフェイスでは使用できなくなりましたが、Workfront データに影響が及ぶ場合があります。これにより、レポートやダッシュボードのレイアウトテンプレート（共有先など）によって影響するフィールドに不整合が生じる可能性があります。」
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 3845794a0b1b610d821f5653c06d0cce77d58f2e
workflow-type: ht
source-wordcount: '192'
ht-degree: 100%

---


# レイアウトテンプレート：レイアウトテンプレートが原因でレポートに不整合が生じる

クラシック[!DNL Workfront]エクスペリエンスのレイアウトテンプレートは、[!DNL Workfront]インターフェイスでは使用できなくなりましたが、[!DNL Workfront]データに影響が及ぶ場合があります。これにより、レポートやダッシュボードのレイアウトテンプレート（[!UICONTROL 共有先]など）によって影響するフィールドに不整合が生じる可能性があります。

**回避策**

API 呼び出しを使用して Classic レイアウトテンプレートを削除します。Workfront にログインする必要があります。

>[!NOTE]
>
>グローバルレイアウトテンプレートおよびシステムレイアウトテンプレートは削除できません。

1. 次の API 呼び出しを使用して、削除するレイアウトテンプレートを見つけます。
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. 削除するレイアウトテンプレートの ID をメモしておきます。
1. 次の API 呼び出しを使用して、セッション ID を見つけます。
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >セッション ID を誰とも共有しないでください。

1. 次の API 呼び出しに、レイアウトテンプレート ID とセッション ID を挿入します。
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. 手順 4 の API 呼び出しをブラウザーの URL バーに貼り付け、Enter キーを押します。

   これにより、レイアウトテンプレートが削除されます。

