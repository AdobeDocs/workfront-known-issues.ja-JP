---
title: 「ホーム：承認済みまたは計画ステータスのプロジェクトのタスクが、マイタスクまたはホームの作業リストに含まれない」
description: ステータスが承認済みまたは計画のプロジェクトのタスクが、ホームに表示されません。 回避策はあります。
hidefromtoc: true
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: ht
source-wordcount: '195'
ht-degree: 100%

---

# ホーム：承認済みまたは計画ステータスのプロジェクトのタスクが、マイタスクまたはホームの作業リストに含まれない

>[!NOTE]
>
>製品チームは現在、この問題の解決策を評価中です。 この問題が解決されると、メンテナンス更新ではなく、製品のお知らせで通達されます。

ステータスが承認済みまたは計画のプロジェクトのタスクが、次のエリアに表示されません。

* クラシックホーム：作業リスト
* 新規ホーム：マイタスクウィジェット

原因は、これらのステータスのプロジェクトのタスクは現在、アイテム数 2000 個のクエリ数制限に含まれていますが、マイタスクやホームの作業リストには表示されないためです。 これにより、タスク数が 2000 未満のユーザーであっても、これらのタスクが表示されないという状況が発生する場合があります。

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
