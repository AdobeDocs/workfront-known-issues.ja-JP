---
title: "ホーム：承認済みまたは計画ステータスのプロジェクトのタスクは、マイタスクまたはホーム作業リストに含まれません"
description: 「承認済みまたは計画済みのステータスを持つプロジェクトのタスクは、ホームに表示されません。 回避策が利用できます。」
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 3%

---


# ホーム：承認済みまたは計画ステータスのプロジェクトのタスクは、「マイタスク」または「ホーム作業リスト」に含まれません

ステータスが「承認済み」または「計画」のプロジェクトのタスクは、次の領域には表示されません。

* クラシックホーム：ワークリスト
* 新規ホーム：マイタスクウィジェット

これは、これらのステータスのプロジェクトのタスクは、現在、2000 項目クエリ制限に含まれていますが、[ マイタスク ] または [ ホーム作業リスト ] には表示されないためです。 これにより、2,000 件未満のタスクを持つユーザーが、これらのタスクを表示できない状況が発生する場合があります。

**回避策**

次のテキストモードフィルターを含むカスタム割り当てレポートを作成します。

割り当てが AWAIDING_ACCEPT の場合は、CURRENT|APPROVED プロジェクトを含めます。

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

割り当てが許可された場合は、現在|承認済み|計画プロジェクトを含めます。

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_最初に報告されたのは 2023年11月6日（PT）です。_
