---
title: 「ボード：複数のユーザーをフィルタリングしてもすべての結果が返されない」
description: 「ユーザーがボードの割り当てフィルターで複数のユーザーをフィルタリングすると、想定されるすべての結果が返されません。」
hidefromtoc: true
feature: Agile
source-git-commit: 073f63610623276f978d15b22cf4a8f294fab44f
workflow-type: ht
source-wordcount: '82'
ht-degree: 100%

---


# ボード：複数のユーザーをフィルタリングしてもすべての結果が返されない

>[!NOTE]
>
>この問題は、2月29日（PT）に修正されました。されました。

ユーザーがボードの割り当てフィルターで複数のユーザーをフィルタリングすると、想定されるすべての結果が返されません。

**回避策**

高度なフィルターを使用して、OR ステートメントで結合された各ユーザーのフィルターを作成します。

_最初に報告されたのは 2024年2月6日（PT）です。_
