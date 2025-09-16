---
title: Workfront Fusion:Jira 検索モジュールがエラーを返す
description: 従来の Jira コネクタで使用されていた検索モジュールでエラーが発生する場合があります。 回避策はあります
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 4%

---


# Workfront Fusion:Jira 検索モジュールがエラーを返す

>[!NOTE]
>
>この問題は、Jira が製品に変更を加えたことが原因です。

従来の Jira コネクタで使用されていた検索モジュールでは、次のエラーが発生する場合があります。

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

これは、Jira 側での非推奨（廃止予定）が原因です。

注意：

* 影響を受けるのは「検索」モジュールのみです。 現時点では、Fusion コネクタで使用される他の Jira API エンドポイントは、この非推奨（廃止予定）の影響を受けません。

* 地理的なロールアウトによって不整合が発生する場合があります。 Atlassian はこの変更を地域的に展開しています。つまり、一部の Jira クラウドインスタンスでは、引き続き一時的に古いエンドポイントをサポートしている可能性があります。 これにより、環境間で動作に一貫性がなくなる可能性があります。

**回避策**

このエラーが発生した場合は、従来の Jira コネクタの検索モジュールを新しいコネクタの検索モジュールに置き換えることができます。 新しいコネクタを使用すると、使用する API バージョンを選択できます。 接続を作成する際は、必ず **API バージョン** フィールドで **V3** を選択します。

_最初に報告されたのは 2025年9月15日（PT）です。_

