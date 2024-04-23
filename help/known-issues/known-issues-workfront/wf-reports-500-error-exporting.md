---
title: 「レポート：レポートの書き出し時に 500 エラーが発生する」
description: ユーザーがレポートを書き出ししようとすると、レポートは書き出されず、エラーが表示されます。回避策はあります。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: ht
source-wordcount: '105'
ht-degree: 100%

---

# レポート：レポートの書き出し時に 500 エラーが発生する

>[!NOTE]
>
>このイシューは 2024年4月5日（PT）に修正されました。

ユーザーがレポートを書き出ししようとすると、レポートは書き出されず、次のエラーが表示されます。

500：「パラメーター」が null /attask/api-internal/report/export であるので、「com.attask.biz.Parameter.getDisplayType()」を呼び出すことができません

この問題は、レポートがプロジェクトレベルのカスタム通貨フィールドを参照する場合に発生します。

**回避策**

カスタム通貨フィールドを参照する列を削除し、レポートを再度書き出します。

_最初に報告されたのは 2024年4月4日（PT）です。_
