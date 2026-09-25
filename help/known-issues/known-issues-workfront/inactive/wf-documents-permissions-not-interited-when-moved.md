---
title: ドキュメント：ドキュメントが新規プロジェクトに移動される場合に権限が継承されない
description: 'ユーザーがドキュメントを異なるプロジェクトに移動すると、ドキュメントは、新規プロジェクトから共有権限を継承しません。 ドキュメントは、プロジェクトが共有されているユーザーに共有されません。 '
feature: Digital Content and Documents
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
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
source-wordcount: '182'
ht-degree: 100%
---
# ドキュメント：ドキュメントが新規プロジェクトに移動される場合に権限が継承されない

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

ユーザーがドキュメントを異なるプロジェクトに移動すると、ドキュメントは、新規プロジェクトから共有権限を継承しません。 ドキュメントは、プロジェクトが共有されているユーザーに共有されません。

**回避策：**

1. プロジェクト、タスク、イシューなど、ドキュメントの親オブジェクトに移動します。

1. 継承された権限の横にある「x」をクリックして、親オブジェクトの共有リストから継承された権限を削除し、「**[!UICONTROL 保存]**」をクリックします。

1. 親オブジェクトの共有リストに戻り、継承された権限の横にある「**[!UICONTROL 取り消し]**」をクリックして、継承された権限を再度追加し、「**[!UICONTROL 保存]**」をクリックします。

または、ドキュメントの ID（[!UICONTROL ドキュメントの詳細]ページの URL に記載されています）をメモして、 [!DNL Workfront] カスタマーサポートに問い合わせすることもできます。

_最初に報告されたのは、2023年1月6日（PT）です。_



<!--CHECK ME - 1 VIEW APRIL-JUNE 2025 (June 11 and 27)-->
