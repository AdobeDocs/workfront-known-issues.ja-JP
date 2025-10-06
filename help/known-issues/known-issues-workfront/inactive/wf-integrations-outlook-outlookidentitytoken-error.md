---
title: 統合：Workfront for Outlook の使用時に outlookIdentityToken エラーが表示される
description: ユーザーが Workfront for Outlook 統合を使用している際、エラーが表示される場合があります。
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# 統合：Workfront for Outlook の使用時に outlookIdentityToken エラーが表示される

>[!NOTE]
>
>Workfront for Outlook との統合は使用できなくなりました。 この記事は近い将来削除される予定です。

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
