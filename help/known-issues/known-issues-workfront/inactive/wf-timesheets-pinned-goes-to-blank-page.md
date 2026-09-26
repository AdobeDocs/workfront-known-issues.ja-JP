---
title: タイムシート：ピン留めされたタイムシートではなく空白のページに移動する
description: ユーザーが Workfront で自分のタイムシートに移動するためにピンをクリックすると、本来のページではなく空白のページに移動します。 回避策はあります。
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# タイムシート：ピン留めされたタイムシートではなく空白のページに移動する

<!--article live for workaround-->

ユーザーが Workfront で自分のタイムシートに移動するためにピンをクリックすると、本来のページではなく空白のページに移動します。

これは、タイムシートの URL が変更されたからです。 URL の末尾の `/own` が、正しい URL ではなくなりました。 ユーザーが `/own` を含む URL をピン留めした場合、このピンをクリックすると空白のページが表示されます。

**回避策**

1. タイムシートのピン留めを解除します。
1. URL の末尾から `/own` を削除します
1. タイムシートを再度ピン留めします。

_最初に報告されたのは、2024年5月7日（PT）です。_
