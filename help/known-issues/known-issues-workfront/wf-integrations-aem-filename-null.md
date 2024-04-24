---
title: 「統合：統合を介してAEMに送信された場合、ファイル名が null になる」
description: 「Workfront統合を通じて大きなファイル（100 MB 超）がAdobe Experience Managerに送信されると、AEMのファイル名が null になります。 」
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: 2110bda5b8f0bec53c0503ce6b3f8da6fce693ca
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 10%

---

# 統合：統合を介してAEMに送信された場合、ファイル名が「null」になる

Workfront統合を通じて大きなファイル（100 MB 超）がAdobe Experience Managerに送信されると、AEMのファイル名が「null」になります。

この問題は、ZIP ファイルと TIF ファイルの両方で報告されています。

**回避策**

次のいずれかの操作を行います。

* ドキュメント名をAEM タイトルにマッピングします。
* AEMで直接ファイル名を入力します。

_最初に報告されたのは 2024年4月23日（PT）です。_

