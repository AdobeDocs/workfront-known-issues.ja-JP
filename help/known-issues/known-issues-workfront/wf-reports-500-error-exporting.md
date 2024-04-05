---
title: 「レポート：レポートのエクスポート時に 500 エラーが発生しました」
description: 「ユーザーがレポートをエクスポートしようとすると、レポートはエクスポートされず、エラーが発生します。 回避策はあります。」
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 1f516bdbea40c2946dec1935b7ada63b28b3451c
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 16%

---


# レポート：レポートの書き出し時に 500 エラーが発生する

ユーザーがレポートのエクスポートを試みると、レポートはエクスポートされず、次のエラーが表示されます。

500: &quot;parameter&quot;が null /attask/api-internal/report/export なので、&quot;com.attask.biz.Parameter.getDisplayType()&quot;を呼び出せません

これは、レポートがプロジェクトレベルのカスタム通貨フィールドを参照する場合に発生します。

**回避策**

カスタム通貨フィールドを参照する列を削除して、レポートを再度エクスポートします。

_最初に報告されたのは 2024年4月4日（PT）です。_
