---
title: Workfront Fusion：日付の出力形式
description: 日付を文字列として出力する場合、日付は UTC または ISO 文字列として出力される場合があります。 これは、マッピングパネル内のロジックによって異なります。
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion：日付の出力形式

日付を文字列として出力する場合、日付は UTC または ISO 文字列として出力される場合があります。 これは、マッピングパネル内のロジックによって異なります。

* 関数内の日付を文字列に結合する場合、文字列は **UTC** 形式で出力されます。
* 関数内で日付を結合しない場合は、**ISO 文字列**&#x200B;として出力されます。

お客様は、`toString`（ISO の場合）または `formatDate` 関数を使用して、出力が必要な形式であることを確認する必要があります。
