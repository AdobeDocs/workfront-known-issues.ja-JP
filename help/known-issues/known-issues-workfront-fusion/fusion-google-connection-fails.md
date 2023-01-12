---
title: 'Workfront Fusion：Google への接続を作成できない'
description: ユーザーが任意の Google コネクタ（Google スプレッドシートや Google ドライブなど）で接続を作成しようとすると、接続が作成されず、様々なエラーメッセージが表示されます。
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '109'
ht-degree: 94%

---

# [!DNL Workfront Fusion]：[!DNL Google] への接続を作成できない

>[!NOTE]
>
>この問題は 2023 年 1 月 10 日に修正されました。

ユーザーが任意の [!DNL Google] コネクタ（[!DNL Google Sheets] や [!DNL Google Drive] など）で接続を作成しようとすると、次のエラーを含むウィンドウが開きます。

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

ユーザーがこのウィンドウを閉じると、[!DNL Fusion] 内で次のエラーが表示され、接続が失敗します。

「[!UICONTROL エラー：前のリクエストの失敗により、リクエストは失敗しました。アクセストークンが指定されていません。]」

_最初に報告されたのは 2022年11月21日です。_
