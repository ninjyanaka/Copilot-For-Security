
![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)  
# Defender XDR インシデント調査

**利用するプラグイン** : Microsoft Defender XDR, Microsoft Intune

**入力パラメータ**: DEFENDER_INCIDENT_ID (Defender XDRのインシデント番号）

**概要**: Defender XDR が検出したインシデントを調査、調査結果をレポートにします。

1.Defender XDRインシデントの要約
```
Defender のインシデント <DEFENDER_INCIDENT_ID>について２００文字で要約してください
```

2. エンティティの調査
```
このインシデントに関連するエンティティについて教えて下さい
```

3. 脅威インテリジェンスの活用
```
そのインシデントのIPv4アドレスのレピュテーションスコアは？
```

4. ユーザーの認証方法の確認
```
そのインシデントに関与した各ユーザに設定されている認証方法を示す。特にMFAが有効になっているかどうかを示す。
```

5. デバイスの調査
```
インシデントの詳細にユーザーが表示されている場合は、そのユーザーが最近使用したデバイスを表示し、ポリシーに準拠しているかどうかを示します。
```

6. パッチの適用状況の確認
```
前の出力にデバイスが表示されている場合は、最も最近チェックインしたデバイスの詳細を Intune から表示します。特に、すべてのオペレーティング・システム・アップデートが最新であるかどうかを示してください。
```

7. CISO向けのレポート作成
```
この調査を要約したエグゼクティブ・レポートを書いてください。CISO向けのレポートです。概要、影響を受けるユーザー、デバイス情報、推奨される対応策、エグゼクティブサマリーを含めてください。
```

イメージ

![Promptbook Defender XDR]()

&nbsp;
[![alt text](../../Images/backtotop.svg)](#Defender)

&nbsp;

**Disclaimer**: これらはサンプルであり、変更される場合があります。
