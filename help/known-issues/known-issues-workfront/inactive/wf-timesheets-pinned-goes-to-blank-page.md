---
title: 「タイムシート：ピン留めされたタイムシートが空白ページに移動する」
description: 「ユーザーがタイムシートに移動するピンをWorkfrontでクリックすると、代わりに空白のページに移動します。 回避策はあります。」
hidefromtoc: true
feature: Timesheets
source-git-commit: d3068f21ba6e1a9a1dd4a9ed78da43cef88f4fde
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 7%

---


# タイムシート：ピン留めされたタイムシートが空白のページに移動する

ユーザーがタイムシートに移動するピンをWorkfrontでクリックすると、代わりに空白のページに移動します。

これは、タイムシートの URL が変更されたためです。 この `/own` url の末尾には、正しい URL が表示されなくなりました。 ユーザーがを含む URL をピン留めした場合 `/own`そのピンが空白のページに誘導されます。

**回避策**

1. タイムシートの固定を解除します。
1. 削除 `/own` URL の末尾から
1. タイムシートを再度ピン留めします。

_最初に報告されたのは 2024年5月7日（PT）です。_
