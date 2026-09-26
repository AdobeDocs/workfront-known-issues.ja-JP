---
title: 承認：承認の委任が間違った日数で設定される
description: ユーザーが個人の休暇をスケジュールし、その時間に対する承認を委任すると、承認委任には、スケジュールされた休暇の前後の日付が含まれることがあります。
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# 承認：承認の委任が間違った日数で設定される

<!--Live for workaround-->

>[!NOTE]
>
>この問題は、問題とは言えないため、クローズされました。

ユーザーが個人の休暇をスケジュールし、その時間に対する承認を委任すると、承認委任には、スケジュールされた休暇の前後の日付が含まれることがあります。

**回避策**

この不一致は、ユーザーのプロファイルのタイムゾーンとユーザーが割り当てたスケジュールのタイムゾーンの違いに起因します。

ユーザーが作業するタイムゾーンごとに一意のスケジュールを作成し、ユーザープロファイルのタイムゾーンに一致するスケジュールに各ユーザーを割り当てることをお勧めします。

_最初に報告されたのは、2022年3月24日（PT）です。_
