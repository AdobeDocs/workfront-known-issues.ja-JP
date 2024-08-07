---
title: 「Workfront Fusion：日付の出力形式」
description: 日付を文字列として出力する場合、日付は UTC または ISO 文字列として出力される場合があります。これは、マッピングパネル内のロジックによって異なります。
hidefromtoc: true
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 87%

---

# Workfront Fusion：日付の出力形式

日付を文字列として出力する場合、日付は UTC または ISO 文字列として出力される場合があります。これは、マッピングパネル内のロジックによって異なります。

* 関数内の日付を文字列に結合する場合、文字列は **UTC** 形式で出力されます。
* 関数内で日付を結合しない場合は、**ISO 文字列**&#x200B;として出力されます。

お客様は、`toString`（ISO の場合）または `formatDate` 関数を使用して、出力が必要な形式であることを確認する必要があります。
