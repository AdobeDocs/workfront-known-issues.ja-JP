---
title: 「プログラム：プログラム所有者を割り当てる際に問題が発生する」
description: 「ユーザーがプログラムを作成してプログラム所有者を割り当てると、この記事で説明する問題が発生します。」
hidefromtoc: true
source-git-commit: f7685aec7811e8741440479d083ef13922b73327
workflow-type: ht
source-wordcount: '95'
ht-degree: 100%

---


# プログラム：[!UICONTROL プログラム所有者]を割り当てる際に問題が発生する

ユーザーがプログラムを作成して[!UICONTROL プログラム所有者]を割り当てると、次の問題が発生します。

* 「[!UICONTROL 500:データベースエラー: BizContext.commit が失敗しました。/attask/api-internal/PRGM/(プログラム ID)]」というエラーが表示される
* ユーザーがプログラムの共有を表示すると、新しい[!UICONTROL プログラム所有者]が追加されたのに対し、継承された権限（プログラムが以前に付与されていた権限）が削除されていないことを確認できます。

_最初に報告されたのは 2022年9月16日です。_

