---
title: 統合：Outlook 用Workfrontを使用する際に outlookIdentityToken エラーが発生する
description: Outlook 用Workfront統合を使用すると、エラーが表示される場合があります。
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# 統合：Outlook 用Workfrontを使用する際に outlookIdentityToken エラーが発生する

Outlook 用Workfront統合を使用すると、次のエラーが表示される場合があります。

```
Unexpected error
Unable to get the outlookIdentityToken
```

**回避策**


このエラーを解決するには、組織のMicrosoft 365 レガシートークンを有効にする必要があります。 これはMicrosoft 365 で行う必要があるので、Workfrontでは組織に対してこれらのトークンを有効にできません。

Microsoft 365 の従来のトークンを有効にする手順については、Microsoft ドキュメントの [ 従来の Exchange Online トークンのオン/オフの切り替え ](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) を参照してください。

レガシー・トークンの詳細については、[Exchange Online のレガシー・トークンをオンにできますか？Microsoft ドキュメントを ](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) 照してください。


_最初に報告されたのは 2025 年 3 月 3 日です。_
