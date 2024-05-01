![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Sample Prompt Library

# Microsoft Entra

- [Entra](#entra)
  - [ユーザー情報](#user-details)
  - [監査ログ](#audit-logs)
  - [サインインログ](#sign-in-logs)
  - [利用規約](terms-of-use-agreements)

***
&nbsp;
## ユーザー情報
<a name="User Details"></a>
- 私のアカウントについて教えて下さい
- ４月1日に、そのユーザーに対してどのようなログイン試行がありましたか? (KQL作成)
- 過去14日間に、ユーザーに対してどのようなログイン試行がありましたか？(KQL作成) 
- ユーザー **_`<UPN>`_**? についてformat-listで詳しく教えてください。
- 過去7日間、ユーザー **_`<UPN>`_**? に対してどのようなログイン試行がありましたか？
- そのユーザーは危険だと思われますか？もしそうなら、なぜですか？
- 過去30日間にこのユーザーのログインに失敗した回数とその理由を教えてください。
- ユーザーに対して有効な認証方法を表示する
- **_`<UPN>`_**?のアカウントで有効になっている認証方法を教えてください。
- **_`<location>`_**? からサインインしたユーザーのサインインログを表示してください
- セキュリティ・グループ **_`<name>`_**? について教えてください。
- **_`<UPN>`_**? のユーザーアカウントのステータスはどうなっていますか？ロックアウトされていますか？
- 過去7日間に削除されたユーザーを表示してください。

&nbsp;
[![alt text](../../Images/backtotop.svg)](#entra)

## 監査ログ

- Microsoft Entraのプラグインを使用して、 **_`<UPN>`_**?の監査ログを見せてください。
- 過去24時間の監査ログを表示する
- 失敗したアクティビティの監査ログを表示する

&nbsp;
[![alt text](../../Images/backtotop.svg)](#entra)

## サインインログ

- 過去24時間のサインイン・ログを表示する
- **_`<UPN>`_**? のサインイン・ログを表示します
    - **_`<Location>`_**? からサインインしたユーザーのサインインログを見せてください。
    - **_`<Application>`_**? のサインインログを見せてください。
    - オペレーティング・システム 'MAC OS 'からのサインイン・ログを見せてください
