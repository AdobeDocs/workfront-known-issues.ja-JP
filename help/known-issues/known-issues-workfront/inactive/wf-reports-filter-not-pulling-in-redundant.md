---
title: レポート：レポートフィルターが期待した結果を返さない
description: レポート内のフィルターは、期待した結果をすべて返さない場合があります。 回避策はあります。
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 100%
---
# レポート：レポートフィルターが期待した結果を返さない

>[!NOTE]
>
>この問題はクローズされました。

レポート内のフィルターは、期待した結果をすべて返さない場合があります。

この問題は、フィルターが特定の条件の結果を返すように設定され、同じ条件のサブセットである結果を返す OR ルールが含まれている場合に発生する可能性があります。

**回避策**

フィルターの OR ブロックには、同じ評価条件が含まれません。

_最初に報告されたのは、2024年3月11日（PT）です。_
