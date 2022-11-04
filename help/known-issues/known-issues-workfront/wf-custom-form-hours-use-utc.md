---
title: カスタムフォーム：計算フィールドの HOUR 関数は UTC を使用します。
description: 「計算フィールドに HOUR 関数が含まれる場合、この関数は期待されるタイムゾーンではなく、UTC に基づいて値を返します。 したがって、HOUR 値に基づく計算は正しくありません。」
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# カスタムフォーム： [!UICONTROL 時間] 計算フィールドの関数は UTC を使用します

>[!NOTE]
>
>この問題は 2022 年 11 月 3 日に修正されました。

計算フィールドに [!UICONTROL 時間] 関数の値は、期待されるタイムゾーンではなく、UTC に基づいて返されます。 したがって、HOUR 値に基づく計算は正しくありません。

_最初に報告されたのは 2022年10月17日です。_

