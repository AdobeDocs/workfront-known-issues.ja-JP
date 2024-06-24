---
title: 「タイムシート：ピン留めされたタイムシートが空白のページに移動する」
description: ユーザーがタイムシートに移動するピンをWorkfrontでクリックすると、代わりに空白のページに移動します。 回避策はあります。
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 74%

---

# タイムシート：ピン留めされたタイムシートではなく空白のページに移動する

<!--article live for workaround-->

ユーザーが Workfront で自分のタイムシートに移動するためにピンをクリックすると、本来のページではなく空白のページに移動します。

これは、タイムシートの URL が変更されたからです。URL の末尾の `/own` が、正しい URL ではなくなりました。ユーザーが `/own` を含む URL をピン留めした場合、このピンをクリックすると空白のページが表示されます。

**回避策**

1. タイムシートのピン留めを解除します。
1. URL の末尾から `/own` を削除します
1. タイムシートを再度ピン留めします。

_最初に報告されたのは 2024年5月7日（PT）です。_
