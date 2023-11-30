---
title: 「レポート：レポートの書き出し時に 500 エラーが発生する」
description: ユーザーがレポートを書き出ししようとすると、書き出しは 500 エラーで失敗します。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 100%

---

# レポート：レポートの書き出し時に 500 エラーが発生する

>[!NOTE]
>
>この問題は、2023年11月30日に修正されました。

ユーザーがレポートを書き出ししようとすると、書き出しは次のエラーで失敗します。

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

これは、`valueexpression` を使用して `lastNote` メモテキストを参照するレポートで報告されています。

_最初に報告されたのは 2023年11月8日（PT）です。_
