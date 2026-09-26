---
title: Workfront Fusion：フィールドがモジュールから欠落している
description: ユーザーが Workfront Fusion でモジュールを設定している際、使用可能なオプションからフィールドが欠落していることに気づく場合があります。 この問題は、ユーザーがカスタムフィールドを更新し、過去 1 時間以内にシナリオ designer を使用した場合に発生することがあります。
feature: Workfront Fusion
exl-id: c5d2d11c-ff31-4189-a630-b0248c02134e
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
source-wordcount: '139'
ht-degree: 100%
---
# Workfront Fusion：フィールドがモジュールから欠落している

ユーザーが Workfront Fusion でモジュールを設定している際、使用可能なオプションからフィールドが欠落していることに気づく場合があります。 この問題は、ユーザーがカスタムフィールドを更新し、過去 1 時間以内にシナリオ designer を使用した場合に発生することがあります。

これは、Workfront／「フィールドを監視」モジュールで報告されています。

**回避策**

この問題は、Workfront Fusion のキャッシュが原因です。 キャッシュは 1 時間ごとに更新されるので、1 時間待ってから、もう一度試してください。

_最初に報告されたのは 2024年2月2日（PT）です。_
