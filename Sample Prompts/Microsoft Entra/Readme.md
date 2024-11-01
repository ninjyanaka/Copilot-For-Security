![Security CoPilot Logo](https://github.com/ninjyanaka/Copilot-For-Security/blob/main/Promptbook%20samples/ic_fluent_copilot_64_64%402x.png)
# Microsoft Copilot for Security Sample Prompt Library

# Microsoft Entra

- [Entra](#entra)
  - [ユーザー情報の調査](#user-details)
  - [監査ログ](#audit-logs)
  - [サインインログ](#sign-in-logs)
  - [利用規約](terms-of-use-agreements)

***
&nbsp;
## ユーザー情報の調査
<a name="User Details"></a>
```
<User_UPN>　について教えて
```
もしくは
```
私について教えて
```
```
上記のユーザの Defender Identity Summary を表示して
```
```
上記のユーザーに関連付けられているデバイスは？
```
```
過去7日間、ユーザー <UPN> に対してどのようなログイン試行がありましたか？
```
```
上記のユーザーにはどのような認証方法が設定されていますか？
```
```
過去30日間にこのユーザーのログインに失敗した回数とその理由を教えてください
```
```
上記ユーザーの過去7日間の監査ログを表示する
```
```
過去7日間に削除されたユーザーを表示して
```

&nbsp;
[![alt text](../../Images/backtotop.svg)](#entra)

## 監査ログ

```
Microsoft Entraのプラグインを使用して、<UPN> の監査ログを表示する
```
```
過去24時間の監査ログを表示する
```
```
失敗したアクティビティの監査ログを表示する
```
```
パスワードを頻繁に変更したユーザーを表示する
```

&nbsp;
[![alt text](../../Images/backtotop.svg)](#entra)

## サインインログ

```
過去24時間のサインイン・ログを表示する。
```
```
<UPN>が最後にサインインした日時を表示する
```
```
<UPN>　のサインイン・ログを表示する
```
```
<Location> からサインインしたユーザーのサインインログを表示する
```
```
<Application> のサインインログを表示する
```
```
過去14日間の非管理対象デバイスからのサインイン・ログを表示し、関連するエンティティをリストアップする
```

&nbsp;
[![alt text](../../Images/backtotop.svg)](#entra)

## Terms of Use Agreements

```
このテナントにおけるユーザー <UPN> の利用規約をすべてリストアップする
```

&nbsp;
[![alt text](../../Images/backtotop.svg)](#entra)

&nbsp;

**Disclaimer**: これらはサンプルであり、変更される場合があります。
