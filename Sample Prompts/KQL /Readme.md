![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Sample Prompt Library

# NL2KQL (Natural Language to KQL)

NL2KQLは自然言語（NL）をKusto Query Language（KQL）のクエリに変換し、セキュリティアナリストがデータを発見し、KQLクエリを構築し、教育的な形式でKQLを学ぶための効果的な方法を提供します。

- Security CopilotスタンドアロンおよびM365D埋め込み体験と統合
- Defender Advanced Huntingテーブルおよび主要なSentinelデータテーブルをサポート

## Defender 
```
先週、疑わしい、あるいは不可能な移動があった個人アカウントは？
```
```
過去72時間以内にローカルデバイスへのログイン失敗回数が最も多いユーザー5人を表示してください。
```

* Defender に特化したKQLを希望する場合には、”NL2KQL for Defender を使用して、” をプロンプトの先頭に挿入すると効果的です。


## Sentinel 
