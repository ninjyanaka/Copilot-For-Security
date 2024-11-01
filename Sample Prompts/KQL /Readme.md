![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Sample Prompt Library

# NL2KQL (Natural Language to KQL)

NL2KQLは自然言語（NL）をKusto Query Language（KQL）のクエリに変換し、セキュリティアナリストがデータを発見し、KQLクエリを構築し、教育的な形式でKQLを学ぶための効果的な方法を提供します。

- Security CopilotスタンドアロンおよびM365D埋め込み体験と統合
- Defender Advanced Huntingテーブルおよび主要なSentinelデータテーブルをサポート

## Defender 
```
NL2KQL for Defender XDR を使用して、先週、疑わしい、あるいは不可能な移動があった個人アカウントは？
```
```
NL2KQL for Defender XDR を使用して、過去72時間以内にローカルデバイスへのログイン失敗回数が最も多いユーザー5人を表示して
```
```
NL2KQL for Defender XDR を使用して、マルウェアの脅威に関連するすべてのEmail添付ファイルとEmailイベントを取得して
```
```
NL2KQL for Defender XDR を使用して、過去１週間、ネットワーク接続障害の多かった上位5台のデバイスを表示してください。デバイス名、OSも含む
```
```

```

* Defender に特化したKQLを希望する場合には、”NL2KQL for Defender XDR を使用して、” をプロンプトの先頭に挿入すると効果的です。


## Sentinel 

```
以下の情報を使用して、Microsoft Sentinel用の適切なKQLクエリを生成して。
テーブル = SecurityAlert
時間/日付の範囲 = 3日間
クエリ = 最も深刻なアラートの上位数と、データに表示される件数
表示 = アラート名と危険度と件数のみ
```
```
NL2KQL for Sentinel を使用して、異常な場所からのログインや、普段使用しないデバイスやIPアドレスからのログインを調べて
```
```
NL2KQL for Sentinel を使用して、異常なファイル共有アクセスや不正なリモートデスクトップアクセスを調べて
```
```
NL2KQL for Sentinel を使用して、攻撃者が権限昇格やバックドア設置のために行う、レジストリキーやシステムファイルの改変の動作が行われた調べて
```
```
NL2KQL for Sentinel を使用して、特定のポートに対して短時間で多くのリクエストが発生しているデバイスを調べて
```
```
NL2KQL for Sentinel を使用して、Malicious URLをクリックしたユーザーを教えて
```

* Sentinel に特化したKQLを希望する場合には、”NL2KQL for Defender XDR を使用して、” 、もしくは、”Microsoft Sentinel用の適切なKQLクエリを生成して”の文言をプロンプトの先頭に挿入すると効果的です。
