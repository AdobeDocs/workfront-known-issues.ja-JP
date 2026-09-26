---
title: カスタムフォーム：クロスオブジェクトのカスタムフォームを編集するには、管理または編集アクセス権が必要です
description: ユーザーが管理または編集アクセス権のみを許可されるクロスオブジェクトを含むフォームを作成してから、そのオブジェクトタイプを削除する場合、カスタムフォームは、フィールドを編集するための管理または編集アクセス権を引き続き必要とします。 フィールドには管理または編集アクセス権が必要だということを示す視覚的な表示がなく、フォームをリセットする方法もありません。
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 92%
---
# カスタムフォーム：クロスオブジェクトのカスタムフォームでフィールドを編集するには、[!UICONTROL 管理]または[!UICONTROL 編集]アクセス権が必要

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>この問題はクローズされました

ユーザーが[!UICONTROL 管理]または[!UICONTROL 編集]アクセス権のみを許可されるクロスオブジェクトを含むフォームを作成してから、そのオブジェクトタイプを削除する場合、カスタムフォームは、フィールドを編集するための[!UICONTROL 管理]または[!UICONTROL 編集]アクセス権を引き続き必要とします。 フィールドには管理または編集アクセス権が必要だということを示す視覚的な表示がなく、フォームをリセットする方法もありません。

**回避策**

1. デフォルト値を含むフォームを設定する場合、フォームにセクション区切りを追加します。
2. セクション区切りをフォームの先頭に移動します。
3. フォームを保存します。
4. 先ほど追加したセクション区切りを削除して、フォームを再保存します。

_最初に報告されたのは、2022年11月9日（PT）です。_
