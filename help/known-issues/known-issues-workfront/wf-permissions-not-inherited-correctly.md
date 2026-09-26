---
title: 権限：オブジェクトの権限が正しく継承されない
description: 継承された権限がオブジェクトに正しく適用されていません。 この問題は、継承される権限が複雑であるために発生する可能性があります。
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# 権限：オブジェクトの権限が正しく継承されない

>[!NOTE]
>
>製品チームは現在、この問題の解決策を評価中です。製品の強化が必要になる可能性があります。 製品の機能強化は、メンテナンス更新ではなく、製品のお知らせで連絡します。

継承された権限がオブジェクトに正しく適用されていません。 この問題は、継承される権限が複雑なために発生する可能性があり、以下の影響を受ける場合があります。

* オブジェクトが多数のユーザーと共有される
* 継承される権限の変更によって、多数のオブジェクトが影響を受ける

**回避策**

オブジェクトのサイズや複雑さを制限すると、この問題を回避できます。 親オブジェクトの下に置く子オブジェクトの数を 10,000 個以下にすることをお勧めします。

_最初に報告されたのは、2025年3月21日（PT）です。_
