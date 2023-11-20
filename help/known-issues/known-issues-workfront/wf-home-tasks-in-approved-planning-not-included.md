---
title: 「ホーム：承認済みまたは計画ステータスのプロジェクトのタスクが、マイタスクまたはホームの作業リストに含まれない」
description: 「ステータスが承認済みまたは計画のプロジェクトのタスクが、ホームに表示されません。回避策はあります。」
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: ht
source-wordcount: '166'
ht-degree: 100%

---


# ホーム：承認済みまたは計画ステータスのプロジェクトのタスクが、マイタスクまたはホームの作業リストに含まれない

ステータスが承認済みまたは計画のプロジェクトのタスクが、次のエリアに表示されません。

* クラシックホーム：作業リスト
* 新規ホーム：マイタスクウィジェット

原因は、これらのステータスのプロジェクトのタスクは現在、アイテム数 2000 個のクエリ数制限に含まれていますが、マイタスクやホームの作業リストには表示されないためです。これにより、タスク数が 2000 未満のユーザーであっても、これらのタスクが表示されないという状況が発生する場合があります。

**回避策**

次のテキストモードフィルターを含むカスタム割り当てレポートを作成します。

割り当てが AWAITING_ACCEPTANCE の場合は、CURRENT|APPROVED プロジェクトを含めます。

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

割り当てが ACCEPTED の場合は、CURRENT|APPROVED|PLANNING プロジェクトを含めます。

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
