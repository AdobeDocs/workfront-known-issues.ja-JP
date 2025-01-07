---
title: プルーフ：Web キャプチャプルーフが生成されない
description: ユーザーが web キャプチャプルーフを作成しようとすると、プルーフが正常に生成されません。
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# プルーフ：Web キャプチャプルーフが生成されない

>[!NOTE]
>
>この問題は、設計どおりの動作であるため、クローズされました。次の回避策を参照してください。

ユーザーが web キャプチャプルーフを作成しようとすると、プルーフが正常に生成されません。

**回避策**

この問題は、特定の PDF ファイルのプルーフ生成時間が長いことが原因で発生します。生成タイムアウトをデフォルトの 30 秒から増やすには、プルーフ管理者のアカウントレベルの処理設定で以下のプロパティを編集します。

`WebCaptureNavigationTimeout -> 120`

_最初に報告されたのは 2024年10月3日（PT）です。_
