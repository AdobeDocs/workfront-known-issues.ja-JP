---
title: レイアウトテンプレート：レイアウトテンプレートを通じてタスクの概要に追加した際に、カスタムデータフィールドが表示されない
description: 管理者がレイアウトテンプレートを通じて「タスクの概要」セクションにカスタムデータフィールドを追加した際、「タスクの概要」セクションを表示するユーザーに対してそのフィールドは空として表示されます。
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 100%
---
# レイアウトテンプレート：レイアウトテンプレートを通じてタスクの概要に追加した際に、カスタムデータフィールドが表示されない

>[!NOTE]
>
>この問題は、設計どおりの動作であるため、クローズされました。 次の回避策を参照してください。

管理者がレイアウトテンプレートを通じて「タスクの概要」セクションにカスタムデータフィールドを追加した際、「タスクの概要」セクションを表示するユーザーに対してそのフィールドは空として表示されます。

**回避策**

カスタムフィールド名に、ピリオド「.」を使用しないで、 この問題を回避します。 「必要に応じて、概要」セクションのカスタムフィールドのラベルを変更すると、ピリオドを含めることができます。

_最初に報告されたのは 2024年10月2日（PT）です。_
