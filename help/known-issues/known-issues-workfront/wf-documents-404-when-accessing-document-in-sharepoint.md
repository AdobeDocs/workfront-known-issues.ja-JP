---
title: 「書類：SharePointからリンクされたドキュメントにアクセスする際に 404 エラーが発生しました」
description: 「ユーザーがSharePoint経由でリンクされたドキュメントにアクセスしようとすると、404 エラーのページが表示されます。」
hidefromtoc: true
source-git-commit: c95d478b78e26e4f0243e9b9ae69ecfbc016d696
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 4%

---


# ドキュメント：からリンクされたドキュメントにアクセスする際に 404 エラーが発生しました [!DNL SharePoint]

<!--This issue is on the WF and WFP TOCs-->

ユーザーが、 [!DNL SharePoint]をクリックすると、次のエラーが発生したページが表示されます。

&quot;[!UICONTROL エラー 404:ページが見つかりません。 このページは使用できません。 URL を確認するか、別のページにアクセスしてみてください。]&quot;

これは既知の問題です [!DNL SharePoint] サイトのリンクに「@」記号が含まれている場合に発生する問題。

**回避策**

[!DNL SharePoint] では、短い url を生成し、それをリンクに使用することをお勧めします。

_最初に報告されたのは 2023年3月14日（PT）です。_

