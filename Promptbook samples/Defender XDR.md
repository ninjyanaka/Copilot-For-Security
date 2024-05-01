
![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)  
# Defender XDR インシデント調査

**利用するプラグイン** : Microsoft Defender XDR, Microsoft Intune

**入力パラメータ**: DEFENDER_INCIDENT_ID (Defender XDRのインシデント番号）

**概要**: Defender XDR が検出したインシデントを調査、調査結果をレポートにします。


***
&nbsp;
## Defender XDR 

 ```
Defender のインシデント <DEFENDER_INCIDENT_ID>について200文字で要約してください。
 ```
 ```
このインシデントのエンティティについて教えて下さい。
 ```
 ```
そのインシデントのIPv4アドレスのレピュテーションスコアは？
 ```
```
そのインシデントに関連する各ユーザに設定されている認証方法を示す。特にMFAが有効になっているかどうかを示す。
```
```
前のアウトプットにデバイスが表示されている場合は、最も最近チェックインしたデバイスの詳細を Intune から表示します。特に、すべてのオペレーティング・システム・アップデートが最新であるかどうかを示してください。
```
```
ユーザーにインシデントが発生した旨、対応方法について説明するサンプルを作成してください。
```

```
この調査を要約したエグゼクティブ・レポートを書いてください。CISO向けのレポートです。概要、影響を受けるユーザー、デバイス情報、推奨される対応策、エグゼクティブサマリーを含めてください。。
```

&nbsp;

## Microsoft Sentinel

 ```
Sentinel のインシデント <SENTINEL_INCIDENT_ID>について200文字で要約してください。
 ```


&nbsp;

免責事項：これらはサンプルであり、変更される場合があります。
