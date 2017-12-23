---
layout: post
title:  "XP投げ銭bot「XPちゃん」の使い方"
date:   2017-12-15 19:00:00 +0900
categories: official
author: 依田
---
## XPちゃんとは
XPちゃん[@tip_XPchan](https://twitter.com/tip_XPchan)とは、XP-JPで作られたTwitterを利用したXP投げ銭サービスです。  
XPちゃんに話しかけることでXPアドレスを作成することができます。  

# 目次(TOC)
- [コマンド一覧](#コマンド一覧)
- [CommandList](#commandlist)
- [注意事項](#注意事項)
- [Caution](#caution)

<br>
## コマンド一覧

- tip
```
@tip_XPchan tip @[ユーザー名] [数量]
```
指定したTwitterアカウントあてにXPを送る

- balance
```
@tip_XPchan balance
```
Twitterアカウントに紐づいたアドレスの残高を表示する

- deposit
```
@tip_XPchan deposit
```
Twitterアカウントに紐づいたアドレスを表示する

- donate
```
@tip_XPchan donate [数量]
```
開発者に支援XPを送る

- withdraw
```
@tip_XPchan withdraw [アドレス] [数量]
```
XPアドレスに数量分のXPを送金する

- withdrawall
```
@tip_XPchan withdrawall [アドレス]
```
XPアドレスに全額XPを送金する

## CommandList

- tip
```
@tip_XPchan tip @[UserName] [Amount]
```
Send XP to TwitterUser

- balance
```
@tip_XPchan balance
```
Show Balance

- deposit
```
@tip_XPchan deposit
```
Show Address

- donate
```
@tip_XPchan donate [Amount]
```
Donate for developers

- withdraw
```
@tip_XPchan withdraw [Address] [Amount]
```
Send an amount of XP to address

- withdrawall
```
@tip_XPchan withdrawall [Address]
```
Send your full amount XP to address

## 注意事項
@tip_XPchanはXP-JP有志による実験的なサービスです。  
何らかの原因で残高が消滅する可能性もあります。  
botには投げ銭用の少額のみ入金してください。  
アプリ連携によっては勝手にツイートするものもあるのでご注意ください。

## Caution  
@ tip_XPchan is an experimental service by XP-JP.
There is a possibility that the balance may disappear for some reason.
Please credit only a small amount for the tip on the bot.
