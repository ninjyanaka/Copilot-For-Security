![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)  
# 疑わしいユーザーの分析

**利用するプラグイン** : Microsoft Entra, Microsoft Intune,Natural language to KQL for Microsoft Defender XDR

**入力パラメータ**: UPN (ユーザー プリンシパル名) 

**概要**: Identity Protection 機能等で検出した疑わしいユーザの調査を行い、分析結果のレポートを作成

1.ユーザーの基本情報を把握
 ```
<UPN> について教えて下さい
 ```
2. ユーザーのアカウントステータスを確認
 ```
<UPN> のユーザーアカウントのステータスはどうなっていますか？ロックアウトされていますか?
 ```
3. ログイン履歴
 ```
過去14日間にこのユーザーがログインに失敗した回数とその理由を教えてください。
 ```
4. ユーザーがサインインした場所
```
サインインに使用した場所とIPアドレスは何ですか？
```
5. ユーザのリスクを把握 
```
このユーザーは、危険だと思われますか？もしそうなら、なぜですか？
```
6. 改善策の提示
```
ユーザーのリスクを軽減するための改善策を提案する。
```
7. レポート作成
```
潜在的にリスクのあるユーザに関する洞察をまとめたエグゼクティブ・レポートを作成します。まず、ユーザ・プリンシパル名（UPN）、出身国、設定されている認証方法、ログイン失敗の記録など、ユーザのメタデータの詳細を記載します。続いて、特定されたリスクに対処するために改善が必要な主要分野を箇条書きにする。その後、浮き彫りになった懸念を改善することを目的とした緩和策を、首尾一貫した段落にまとめます。
```

イメージ

![Promptbook Risky User](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/Promptbook-suspcious%20user%20risk.png)
