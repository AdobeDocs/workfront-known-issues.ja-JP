---
title: プルーフ：Web キャプチャプルーフが生成されない
description: ユーザーが web キャプチャプルーフを作成しようとすると、プルーフが正常に生成されません。
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 59%

---

# プルーフ：Web キャプチャプルーフが生成されない

>[!NOTE]
>
>この問題は、設計どおりの動作であるため、クローズされました。以下の回避策を参照してください。

ユーザーが web キャプチャプルーフを作成しようとすると、プルーフが正常に生成されません。

**回避策**

この問題は、特定のPDFファイルのプルーフの生成時間が長いことが原因です。 生成タイムアウトをデフォルトの 30 秒から増やすには、Proof 管理のアカウントレベルにある処理設定の以下のプロパティを編集します。

`WebCaptureNavigationTimeout -> 120`

_最初に報告されたのは 2024年10月3日（PT）です。_
