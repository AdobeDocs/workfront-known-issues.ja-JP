---
title: 「統合：統合を介して AEM にファイルを送信すると、ファイル名が null になる」
description: 「Workfront 統合を介して Adobe Experience Manager に大きなファイル（100 MB 以上）を送信すると、AEM でファイル名が null になります。」
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: e24d266002a913e5c6e2d5e40e9dad36deff541a
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 52%

---

# 統合：ドキュメント統合に送信された際にファイル名が「null」になる

>[!NOTE]
>
>この問題は、2024年5月8日（PT）に修正されました。

Workfront統合を使用して大きなファイル（100 MB 超）がドキュメントプロバイダーに送信されると、ドキュメントプロバイダーのファイル名が「null」になります。

この問題は、ZIP ファイルと TIF ファイルの両方で報告されています。

**回避策**

次のいずれかの操作を行います。

* ドキュメント名をドキュメントプロバイダーのタイトルにマッピングします。
* ファイル名をドキュメントプロバイダーに直接入力します。

_最初に報告されたのは 2024年4月23日（PT）です。_

