---
title: "Workfront Fusion：日付の出力形式"
description: 「日付が文字列として出力される場合、日付は UTC または ISO 文字列として出力される場合があります。 これは、マッピングパネル内のロジックに依存します。」
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion：日付の出力形式

Dates が String として出力される場合、日付は UTC または ISO 文字列として出力されます。 これは、マッピングパネル内のロジックに依存します。

* 関数内の Date が文字列に結合されている場合、その文字列は **UTC** 形式を使用します。
* 関数内で Date が結合されていない場合、 **ISO 文字列**.

お客様は、 `toString` （ISO の場合）または `formatDate` 関数を使用して、出力が必要な形式になっていることを確認します。
