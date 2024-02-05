---
title: "Workfront Fusion: Field is missing from module"
description: 「ユーザーがWorkfront Fusion でモジュールを設定しているときに、使用可能なオプションにフィールドがないことに気付くかもしれません。 これは、ユーザーがカスタムフィールドを更新し、過去 1 時間以内にシナリオデザイナーを使用した場合に発生する可能性があります。」
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: aad77d690cef72beb1543c442ee557e768777150
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 0%

---


# Workfront Fusion：モジュールにフィールドがありません

ユーザーがWorkfront Fusion でモジュールを設定しているときに、使用可能なオプションにフィールドがないことに気付く場合があります。 これは、ユーザーがカスタムフィールドを更新し、過去 1 時間以内にシナリオデザイナーを使用した場合に発生する可能性があります。

これは、 Workfront /監視フィールドモジュールで報告されています。

**回避策**

この問題は、Workfront Fusion のキャッシュが原因です。 キャッシュは 1 時間ごとに更新されるので、1 時間待ってから再試行してください。

_最初のレポートは 2024 年 2 月 2 日 (PT) です。_
