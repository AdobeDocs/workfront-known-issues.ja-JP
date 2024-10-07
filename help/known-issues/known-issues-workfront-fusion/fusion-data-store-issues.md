---
title: 「Workfront Fusion：データストアの問題」
description: 「データストアのブール値フィールドに関する次の問題が報告されています。データストアは、値が「EMPTY」のフィールドに対して値を返さず、ユーザーは、データストアで直接 FALSE に値を設定できません。」
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: ac07686c60025fab3ab815a6321271cd401355f4
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 100%

---


# Workfront Fusion：データストアの問題

>[!NOTE]
>
>この記事は 2024年9月26日（PT）に修正されました。

データストアのブール値フィールドに関する次の問題が報告されています。

* データストアは、値が「EMPTY」のフィールドに対して値を返しません。
* ユーザーは、データストアで直接 FALSE に値を設定できません。

**回避策**

FALSE に値を設定するには、適切なレコードを更新モジュールを使用します。

_最初に報告されたのは 2024年9月19日（PT）です。_
