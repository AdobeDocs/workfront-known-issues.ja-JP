---
title: 'カスタムフォーム：クロスオブジェクトのカスタムフォームでフィールドを編集するには、管理または編集アクセス権が必要'
description: ユーザーが管理または編集アクセス権のみを許可されるクロスオブジェクトを含むフォームを作成してから、そのオブジェクトタイプを削除する場合、カスタムフォームは、フィールドを編集するための管理または編集アクセス権を引き続き必要とします。フィールドには管理または編集アクセス権が必要だということを示す視覚的な表示がなく、フォームをリセットする方法もありません。
hidefromtoc: true
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
source-git-commit: d8285b98fc4cabf099994de64c466e829061611c
workflow-type: ht
source-wordcount: '184'
ht-degree: 100%

---

# カスタムフォーム：クロスオブジェクトのカスタムフォームでフィールドを編集するには、[!UICONTROL 管理]または[!UICONTROL 編集]アクセス権が必要

>[!NOTE]
>
>この問題はクローズされました

ユーザーが[!UICONTROL 管理]または[!UICONTROL 編集]アクセス権のみを許可されるクロスオブジェクトを含むフォームを作成してから、そのオブジェクトタイプを削除する場合、カスタムフォームは、フィールドを編集するための[!UICONTROL 管理]または[!UICONTROL 編集]アクセス権を引き続き必要とします。フィールドには管理または編集アクセス権が必要だということを示す視覚的な表示がなく、フォームをリセットする方法もありません。

**回避策**

1. デフォルト値を含むフォームを設定する場合、フォームにセクション区切りを追加します。
2. セクション区切りをフォームの先頭に移動します。
3. フォームを保存します。
4. 先ほど追加したセクション区切りを削除して、フォームを再保存します。

_最初に報告されたのは 2022年11月9日です。_
