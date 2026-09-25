---
title: ユーザー：新規ユーザーに「承認保留中」バッジが表示される
description: Workfront の新規ユーザーは、ユーザーリストに「承認保留中」バッジ付きで表示される場合があります。 このバッジは数分以上保持され、ページが更新されても残ります。
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: 254442ca-6997-5cfa-963e-f420870aea53
    internal-label: People Teams and Groups
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%
---
# ユーザー：新規ユーザーに「承認保留中」バッジが表示される

>[!NOTE]
>
>この問題は、Adobe Admin Console に移行した組織で発生する場合があります。

Workfront の新規ユーザーは、ユーザーリストに「承認保留中」バッジ付きで表示される場合があります。 このバッジは数分以上保持され、ページが更新されても残ります。

この問題は、ユーザーがスプレッドシートや Workfront Kick-Start などの大きなバッチでアップロードされると悪化します。

バッジが数分後に消え、ページを更新しても存在しなくなることが望まれます。

## 回避策

これは、Workfront に追加されたユーザーが Adobe Admin Console と同期されない場合に発生します。

次の回避策をお勧めします。

### 個人ユーザーの解決

ユーザーリストで個人ユーザーを解決できます。

1. ユーザーリストで 1 人または複数のユーザーを選択します。
1. リストヘッダーの 3 点メニューをクリックします。
1. 「**承認**」を選択します。
1. 数分後にページを更新します。

### 大きなバッチで追加されたユーザーの解決

大きなバッチで追加されたユーザーを解決するには、ユーザーのバッチを Adobe Admin Console に直接追加します。

手順については、アドビドキュメントの[複数ユーザーの管理 | CSV の一括アップロード](https://helpx.adobe.com/jp/enterprise/using/bulk-upload-users.html)を参照してください。


_最初に報告されたのは、2025年5月8日（PT）です。_
