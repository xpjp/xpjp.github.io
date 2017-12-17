---
layout: post
title:  "ウォレットのノードが繋がりにくい問題への対処について"
date:   2017-12-18 1:30:00 +0900
categories: official
author: 依田
---
ウォレットを新規導入した場合、ノードに繋がりにくい現象が[#help](https://discord.gg/FTjxxNn)において多数報告を受けておりました。  
このたび、XP-JP Lab有志が独自で日本国内にノードを立てましたので、Explorerで表示されるノードに加えて、こちらもご利用いただけますと改善されると思います。  

以下を、`c:<user>\AppData\Roaming\XP` の中にある`XP.conf`へ画像のように貼り付けてください。  
```
addnode=45.32.45.43
addnode=45.77.2.104
addnode=45.63.94.41
addnode=45.32.220.209
addnode=45.63.65.48
```  
![スクショ1]({{site.baseurl}}/images/17-12/Wallet_Node.png)  
