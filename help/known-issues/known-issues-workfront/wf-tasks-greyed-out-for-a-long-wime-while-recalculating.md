---
title: 「タスク：タイムラインを再計算する際に、タスクの日付が長時間グレーアウトされる」
description: 「ユーザーがタイムラインの再計算をトリガーするタスクリストを変更すると、そのタイムラインの影響を受ける他のタスクも再計算されます。この処理が行われている間、他のタスクの影響を受ける日付はグレーアウトされます。この問題では、タスクが長期間グレー表示のままになります。」
hidefromtoc: true
feature: Tasks
source-git-commit: 0bec78610e0e035d89b60a53d08cf07ef80c0753
workflow-type: ht
source-wordcount: '149'
ht-degree: 100%

---


# タスク：タイムラインを再計算する際に、タスクの日付が長時間グレーアウトされる

ユーザーがタイムラインの再計算をトリガーするタスクリストを変更すると、そのタイムラインの影響を受ける他のタスクも再計算されます。この処理が行われている間、他のタスクの影響を受ける日付はグレーアウトされます。この問題では、タスクが長期間グレー表示のままになります。

これらがグレー表示となっている間にこれらの日付に加えられた変更は、保存されます。

**回避策**

ページを更新します。

_最初に報告されたのは 2023年10月12日（PT）です。_