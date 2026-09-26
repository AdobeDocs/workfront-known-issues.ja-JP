---
title: Workfront Proof:APIまたはWorkfront FusionからWorkfront Proofにアクセスする際に500 エラーが発生する
description: プルーフ API getAllProofs アクションにアクセスすると、Workfront Proof サーバーは次のメッセージを返します。500 Internal Server Error
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof]：[!DNL Workfront Proof] にアクセスすると、500 エラーが発生する（API または [!DNL Workfront Fusion] 経由）

>[!NOTE]
>
>製品チームは現在、この問題の解決策を評価中です。製品の強化が必要になる可能性があります。 製品の機能強化は、メンテナンス更新ではなく、製品のお知らせで連絡します。

<!--This article is on Proof and Fusion TOCs-->

ユーザーが [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] アクションにアクセスすると、サーバーは次のメッセージを返します。

[!UICONTROL 500 内部サーバー エラー]

[!DNL Workfront Fusion] は [!DNL Workfront Proof] モジュールに [!DNL Workfront Proof] API を使用するので、このエラーがモジュールに返され、シナリオが停止する場合があります。

_最初に報告されたのは、2023年4月28日（PT）です。_
