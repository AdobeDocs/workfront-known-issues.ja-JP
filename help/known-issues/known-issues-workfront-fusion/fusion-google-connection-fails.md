---
title: '"Workfront Fusion:Googleへの接続を作成できません'
description: 「ユーザーが任意のGoogleコネクタ (Google Sheet やGoogle Drive など ) で接続を作成しようとした場合、接続は作成されず、様々なエラーメッセージが表示されます。」
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '103'
ht-degree: 3%

---


# [!DNL Workfront Fusion]:への接続を作成できません [!DNL Google]

ユーザーがいずれかの [!DNL Google] コネクタ ( [!DNL Google Sheets] または [!DNL Google Drive]) の場合は、次のエラーで開いたウィンドウが表示されます。

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

ユーザーがこのウィンドウを閉じると、接続が失敗し、内部に次のエラーが表示されます [!DNL Fusion]:

&quot;[!UICONTROL エラー：前のリクエストが失敗したので、リクエストに失敗しました。 アクセストークンが指定されていません。]&quot;

_最初に報告されたのは 2022年11月21日です。_

