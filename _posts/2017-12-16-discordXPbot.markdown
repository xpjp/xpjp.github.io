---
layout: post
title:  "discord bot「XP-BOT」の使い方"
date:   2017-12-16 0:00:00 +0900
categories: official
author: 依田
---
## XP-BOTとは
XP-BOTとは、本家XPコミュニティで作られたdiscordを利用したXP投げ銭サービスです。  
`#bot-spam`で`,register`と打つことでXPアドレスを作成することができます。  
*※BOTの乱用はおやめください。またなるべく混雑時を避けて残高確認をお願いします。*

<br>
## コマンド一覧

- register
```
,register
```
XPのdiscord用walletを作成する  
チャンネルに参加したら`#bot-spam`で最初に行ってください

- balance
```
,balance
```
discordに紐づいたアドレスの残高を表示する

- tip (他の人に)
```
,tip @(宛先人) 数量
```
discordの@(宛先人)宛に数量分のXPを投げ銭する

- tip (アドレス宛に)
```
,tip アドレス 数量
```
XPアドレスに数量分のXPを送金する

- rain
```
,rain 数量
```
discordにオンラインになっている人全員に数量分のXPを均等に分配する  
数量の最小は1000です

## 注意事項
コマンドや数値の間は半角スペースを入れてください  
`,balance`はなるべく混雑を避けて使用してください  
`#bot-spam`チャンネルなどででbotがメンテナンスしていると告知がある場合は書き込まないでください  
コマンドは正しいチャンネルで入力してください  
