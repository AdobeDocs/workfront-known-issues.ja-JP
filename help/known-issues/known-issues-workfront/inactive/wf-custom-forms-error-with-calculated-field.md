---
title: カスタムフォーム：計算フィールドの設定時にエラーが発生する
description: ユーザーがカスタムフォームで計算フィールドを作成または編集する際、計算フィールドの式にカスタムフィールドを含めると、式は無効と見なされます。 「保存」ボタンは無効になっており、ユーザーはカスタムフィールドから移動できません。 さらに、フィールドの下に Whoops メッセージが表示されます。
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
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
source-wordcount: '180'
ht-degree: 94%
---
# カスタムフォーム：計算フィールドを設定する際に[!UICONTROL エラー]が発生する

<!--Requested: Do not delete without approval from Alex Beach-->

>[!NOTE]
>
>このイシューは、2023年1月12日（PT）に修正されました。

ユーザーがカスタムフォームで計算フィールドを作成または編集する際、計算フィールドの式にカスタムフィールドを含めると、式は無効と見なされます。 「[!UICONTROL 保存]」ボタンは無効になっており、ユーザーはカスタムフィールドから移動できません。 さらに、フィールドの下にエラーメッセージが表示されます。

「[!UICONTROL &#x200B; エラーが発生しました。 Workfront にお問い合わせください。問題の原因を確認して修正させていただきます。]」

式からカスタムフィールドを削除すると、ユーザーはフィールドを保存して、フィールドから移動できるようになります。

_最初に報告されたのは 2022年10月11日（PT）です。_
