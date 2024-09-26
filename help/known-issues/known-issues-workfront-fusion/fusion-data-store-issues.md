---
title: 「Workfront Fusion：データストアの問題」
description: 「データストアのブール値フィールドに関して、次の問題が報告されています。データストアが、値が EMPTY のフィールドに値を返さず、ユーザーがデータストアで直接 FALSE に値を設定できません。」
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 2cbde79df7bb110e083f8e8b65b319d9c682e188
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 5%

---


# Workfront Fusion：データストアの問題

データストアのブール値フィールドに関する次の問題が報告されています。

* データストアが、値が EMPTY のフィールドに値を返していません。
* ユーザーは、データストア内で値を直接 FALSE に設定することはできません。

**回避策**

値を FALSE に設定するには、適切なレコードを更新モジュールを使用します。

_最初に報告されたのは 2024年9月19日（PT）です。_
