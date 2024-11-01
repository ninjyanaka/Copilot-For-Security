![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Sample Prompt Library

***
&nbsp;
## Defender XDR 

 ```
Microsoft Defender XDRから、優先すべき重大度の高いインシデントの上位5件を教えて
 ```
 ```
Defender XDR インシデント <DEFENDER_INCIDENT_ID> を要約して
 ```
 ```
該当のインシデントに関連するエンティティを教えて
 ```
 ```
MDTIを使用して、IPアドレス、URLとファイルのハッシュを検証し、レピュテーションを評価して
 ```
```
該当のインシデントに関連する各ユーザに設定されている認証方法を教えて
```
```
このインシデントのエンティティにデバイスが含まれる場合、最新のチェックインしたデバイスの詳細を Intune から表示します。特に、すべてのオペレーティング・システム・アップデートが最新であるかどうかを示してください
```
デバイスが複数の場合
```
<Device Name> のデバイスに関して、最新のチェックインしたデバイスの詳細を Intune から表示します。特に、すべてのオペレーティング・システム・アップデートが最新であるかどうかを示してください
```

```
このインシデントの推奨される対応策を提示してください
```

```
調査結果をエグゼクティブ・レポートにまとめて
```
もしくは
```
このインシデントから得られた主な洞察をまとめたエグゼクティブレポートを作成してください。レポートに続いて、特定されたリスクに対処するために修正が必要な主な領域を箇条書きでリストアップしてください。最後に、これらの懸念事項に対処するための緩和策の概要を説明してください
```

&nbsp;

## Microsoft Sentinel

 ```
Sentinel のインシデント <SENTINEL_INCIDENT_ID> を要約して
 ```
 ```
この Sentinelのインシデントに関連するエンティティを教えて
 ```

 ```
MDTIを使用して、IPアドレス、URLとファイルのハッシュを検証し、レピュテーションを評価して
 ```

 ```
この調査を要約したエグゼクティブレポートを作成すること。技術的でない読者向けに作成すること
 ```


&nbsp;
[![alt text](../../Images/backtotop.svg)](#defender)

&nbsp;

**Disclaimer**: これらはサンプルであり、変更される場合があります。
