---
title: 「Workfront Fusion：フィールドがモジュールから欠落している」
description: 「ユーザーが Workfront Fusion でモジュールを設定している際、使用可能なオプションからフィールドが欠落していることに気づく場合があります。この問題は、ユーザーがカスタムフィールドを更新し、過去 1 時間以内にシナリオデザイナーを使用した場合に発生することがあります。」
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: aad77d690cef72beb1543c442ee557e768777150
workflow-type: ht
source-wordcount: '137'
ht-degree: 100%

---


# Workfront Fusion：フィールドがモジュールから欠落している

ユーザーが Workfront Fusion でモジュールを設定している際、使用可能なオプションからフィールドが欠落していることに気づく場合があります。この問題は、ユーザーがカスタムフィールドを更新し、過去 1 時間以内にシナリオデザイナーを使用した場合に発生することがあります。

これは、Workfront／「フィールドを監視」モジュールで報告されています。

**回避策**

この問題は、Workfront Fusion のキャッシュが原因です。キャッシュは 1 時間ごとに更新されるので、1 時間待ってから、もう一度試してください。

_最初に報告されたのは 2024年2月2日（PT）です。_
