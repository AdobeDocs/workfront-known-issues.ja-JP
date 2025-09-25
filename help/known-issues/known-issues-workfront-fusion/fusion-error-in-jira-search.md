---
title: Workfront Fusion：Jira 検索モジュールがエラーを返す
description: 従来の Jira コネクターで使用されていた検索モジュールでは、エラーが発生する場合があります。回避策はあります
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: ht
source-wordcount: '186'
ht-degree: 100%

---


# Workfront Fusion：Jira 検索モジュールがエラーを返す

>[!NOTE]
>
>この問題は、Jira が製品に加えた変更が原因です。

従来の Jira コネクターで使用されていた検索モジュールでは、次のエラーが発生する場合があります。

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

これは、Jira 側の廃止によるものです。

メモ：

* 影響を受けるのは検索モジュールのみです。現時点では、Fusion コネクターで使用される他の Jira API エンドポイントは、この廃止の影響を受けません。

* 地理的なロールアウトによって不整合が発生する場合があります。Atlassian はこの変更を地域的に展開しています。つまり、一部の Jira クラウドインスタンスでは、引き続き一時的に古いエンドポイントをサポートしている可能性があります。これにより、環境間で動作に一貫性がなくなる可能性があります。

**回避策**

このエラーが発生した場合は、従来の Jira コネクターの検索モジュールを新しいコネクターの検索モジュールに置き換えることができます。新しいコネクターでは、使用する API バージョンを選択できます。接続を作成する際は、「**API バージョン**」フィールドで **V3** を選択してください。

_最初に報告されたのは 2025年9月15日（PT）です。_

