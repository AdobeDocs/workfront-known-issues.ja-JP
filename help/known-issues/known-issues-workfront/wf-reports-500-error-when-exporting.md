---
title: 「レポート：レポートの書き出し時に 500 エラーが発生する」
description: ユーザーがレポートを書き出ししようとすると、書き出しは 500 エラーで失敗します。
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 45cea090d9e54514be9983b5443e7ee54b1f2d94
workflow-type: ht
source-wordcount: '59'
ht-degree: 100%

---

# レポート：レポートの書き出し時に 500 エラーが発生する

ユーザーがレポートを書き出ししようとすると、書き出しは次のエラーで失敗します。

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

これは、`valueexpression` を使用して `lastNote` メモテキストを参照するレポートで報告されています。

_最初に報告されたのは 2023年11月8日（PT）です。_
