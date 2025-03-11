---
title: 統合：Workfront for Outlook の使用時に outlookIdentityToken エラーが表示される
description: ユーザーが Workfront for Outlook 統合を使用している際、エラーが表示される場合があります。
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: fff5428fd0c9a50f20ded044bf0ab251dfde5a6e
workflow-type: ht
source-wordcount: '127'
ht-degree: 100%

---

# 統合：Workfront for Outlook の使用時に outlookIdentityToken エラーが表示される

ユーザーが Workfront for Outlook 統合を使用している際、次のエラーが表示される場合があります。

```
Unexpected error
Unable to get the outlookIdentityToken
```

**回避策**


このエラーを解決するには、組織に対して Microsoft 365 レガシートークンを有効にする必要があります。これは Microsoft 365 で実行する必要があるので、Workfront では組織に対してこれらのトークンを有効にできません。

Microsoft 365 のレガシートークンを有効にする手順について詳しくは、Microsoft ドキュメントの[レガシー Exchange Online トークンのオンとオフを切り替える](https://learn.microsoft.com/ja-jp/office/dev/add-ins/outlook/turn-exchange-tokens-on-off)を参照してください。

レガシートークンについて詳しくは、Microsoft ドキュメントの [Exchange Online レガシートークンを再びオンにできますか？](https://learn.microsoft.com/ja-jp/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on)を参照してください。


_最初に報告されたのは 2025年3月3日（PT）です。_
