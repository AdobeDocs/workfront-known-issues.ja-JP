---
title: 「レポート：レポートの書き出し時に 500 エラーが発生する」
description: ユーザーがレポートをエクスポートしようとすると、レポートはエクスポートされず、エラーが発生します。 回避策はあります。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 27%

---

# レポート：レポートの書き出し時に 500 エラーが発生する

>[!NOTE]
>
>このイシューは 2024年4月5日（PT）に修正されました。

ユーザーがレポートのエクスポートを試みると、レポートはエクスポートされず、次のエラーが表示されます。

500: &quot;parameter&quot;が null /attask/api-internal/report/export なので、&quot;com.attask.biz.Parameter.getDisplayType()&quot;を呼び出せません

これは、レポートがプロジェクトレベルのカスタム通貨フィールドを参照する場合に発生します。

**回避策**

カスタム通貨フィールドを参照する列を削除して、レポートを再度エクスポートします。

_最初に報告されたのは 2024年4月4日（PT）です。_
