---
title: 「カスタムフォーム：計算フィールドの HOUR 関数が UTC を使用する」
description: 計算フィールドに HOUR 関数が含まれる場合、この関数は、期待されるタイムゾーンではなく、UTC に基づいた値を返します。したがって、HOUR 値に基づく計算は正確ではありません。
hidefromtoc: true
exl-id: f4f9fb6e-6226-4603-9518-4c935a644039
source-git-commit: 66e3bc22d8aef2d6287161f4a13fbbe0f3ac99c8
workflow-type: ht
source-wordcount: '90'
ht-degree: 100%

---

# カスタムフォーム：計算フィールドの [!UICONTROL HOUR] 関数が UTC を使用する

>[!NOTE]
>
>この問題は、2022年11月3日に修正されました。

計算フィールドに [!UICONTROL HOUR] 関数が含まれる場合、この関数は、期待されるタイムゾーンではなく、UTC に基づいた値を返します。したがって、HOUR 値に基づく計算は正確ではありません。

_最初に報告されたのは 2022年10月17日です。_
