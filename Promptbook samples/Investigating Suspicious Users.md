![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)  
# 疑わしいユーザーの分析

**利用するプラグイン** : Microsoft Entra, Microsoft Intune

**入力パラメータ**: UserName

**概要**: Identity Protection 機能等で検出した疑わしいユーザの調査を行い、分析結果のレポートを作成

1. 調査対象のユーザーの基本情報を把握
 ```
<UserName> について教えて下さい
 ```
2. 調査対象ユーザーのアカウントステータスを確認
 ```
<UserName>のユーザーアカウントのステータスはどうなっていますか？ロックアウトされていますか?
 ```
