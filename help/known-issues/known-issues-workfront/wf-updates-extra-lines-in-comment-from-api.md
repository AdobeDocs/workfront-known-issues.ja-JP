---
title: "更新： API またはWorkfront Fusion を通じて行われたコメントの余分な行"
description: 「ユーザーが API またはWorkfront Fusion を通じてコメントを送信すると、「更新」領域に表示されるコメントに余分な行が表示されます。 時には行数が多すぎるので、ユーザーは下にスクロールしてコメントの内容を確認する必要があります。」
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 1854e4a003722f1398c703dfba7bc23ef534f81f
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 8%

---


# 更新： API またはを通じて行われたコメントの余分な行 [!DNL Workfront Fusion]

ユーザーが API またはを通じてコメントを送信したとき [!DNL Workfront Fusion]をクリックした場合、「更新」領域に表示されるコメントに余分な行が表示されます。 行数が多すぎるので、ユーザーは下にスクロールしてコメントの内容を確認する必要があります。

この問題は、新しいコメントエクスペリエンスで報告されています。

**回避策**

この問題は、コメント内で送信されたHTML内のスペースまたは改行が原因で発生します。

この問題を回避するには、すべてのHTMLを 1 行に配置し、HTML要素間にスペースや改行を配置しないようにします。

影響を受けたコメントを余分な行を含めずに表示するには、従来のコメントエクスペリエンスに切り替えます。

_最初に報告されたのは 2023年10月27日（PT）です。_