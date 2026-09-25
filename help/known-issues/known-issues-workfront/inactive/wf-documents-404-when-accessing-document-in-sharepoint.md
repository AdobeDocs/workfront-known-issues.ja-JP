---
title: 'Documents: SharePointからリンクされたドキュメントにアクセスすると、404 エラーが発生する'
description: ユーザーが SharePoint 経由でリンクされているドキュメントにアクセスしようとすると、404 エラーのページが表示されます。
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# ドキュメント：[!DNL SharePoint] からリンクされているドキュメントにアクセスする際に 404 エラーが発生する

<!--Requested article. This issue is on the WF and WFP TOCs.-->

ユーザーが [!DNL SharePoint] 経由でリンクされているドキュメントにアクセスしようとすると、次のエラーのページが表示されます。

「[!UICONTROL エラー 404：ページが見つかりません。 このページは使用できません。 URL を確認するか、別のページにアクセスしてみてください。]」

これは、サイトのリンクに「@」記号が含まれている場合に発生する既知の [!DNL SharePoint] イシューです。

**回避策**

[!DNL SharePoint] では、短い URL を生成し、リンクに使用することをお勧めします。

_最初に報告されたのは、2023年3月14日（PT）です。_
