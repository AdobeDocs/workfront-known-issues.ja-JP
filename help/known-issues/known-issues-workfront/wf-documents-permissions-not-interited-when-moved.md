---
title: "ドキュメント：ドキュメントが新規プロジェクトに移動される場合に権限が継承されない"
description: "ユーザーがドキュメントを異なるプロジェクトに移動すると、ドキュメントは、新規プロジェクトから共有権限を継承しません。ドキュメントは、プロジェクトが共有されているユーザーに共有されません。"
hidefromtoc: true
source-git-commit: ca969341423e373a94faa677729fc2dccd9453d6
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 57%

---


# ドキュメント：ドキュメントが新規プロジェクトに移動される場合に権限が継承されない

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--This issue has been closed as won't fix, but no reason.-->

ユーザーがドキュメントを異なるプロジェクトに移動すると、ドキュメントは、新規プロジェクトから共有権限を継承しません。ドキュメントは、プロジェクトが共有されているユーザーに共有されません。

**回避策：**

1. Project、Task、Issue など、ドキュメントの親オブジェクトに移動します。

1. 継承されたアクセス許可の横にある「x」をクリックして、親オブジェクトの共有リストから継承されたアクセス許可を削除し、 **[!UICONTROL 保存]**.

1. 継承された権限を再追加するには、親オブジェクトの共有リストに戻って、 **[!UICONTROL 取り消し]** 継承された権限の横にある「 **[!UICONTROL 保存]**.

または、ドキュメントの ID( [!UICONTROL ドキュメントの詳細] ページ ) および連絡先 [!DNL Workfront] カスタマーサポート。

_最初に報告されたのは 2023年1月6日です。_

