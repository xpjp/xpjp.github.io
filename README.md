# xpjp.github.io

・XPJP公式HPの作成にはJekyllを使用しています。  

Jekyllは静的サイトを生成するためのRuby製のツールです。  
[Jekyll とは何か1](https://app.codegrid.net/entry/jekyll-introduction)  
[Jekyll とは何か2](https://jekyllrb-ja.github.io/)  
[Jekyll 導入方法](https://jekyllrb-ja.github.io/docs/installation/)  

### Jekyllコマンド  
・jekyll build  
・jekyll serve  

### 記事の追加方法  
`./_posts/`にmarkdownファイルを追加することによって記事を追加できます。  
画像は`./images/`に入れています。  


### 記事の書き方  
`2017-12-18-Wallet_Node.markdown`を例にします。  

```  
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

addnode=45.32.45.43
addnode=45.77.2.104
addnode=45.63.94.41
addnode=45.32.220.209
addnode=45.63.65.48
  
![スクショ1]({{site.baseurl}}/images/17-12/Wallet_Node.png)  

```  
・レイアウト、記事タイトル、投稿時間、カテゴリ、著者の記述  
```  
---
layout: post
title:  "ウォレットのノードが繋がりにくい問題への対処について"
date:   2017-12-18 1:30:00 +0900
categories: official
author: 依田
---
```  
layoutはcss設定すれば独自のレイアウトがつくれるハズ  
date順に記事がソートされるので時間を間違えないように  

・画像の追加方法  
```  
![スクショ1]({{site.baseurl}}/images/17-12/Wallet_Node.png)  
```  
このような感じでパスを通せば画像貼れます  

### 記事の追加方法  
`./_faqs/`にmarkdownファイルを追加することによって記事を追加できます。  
画像は`./images/`に入れています。  

### FAQの書き方  
`q0001`を例にします。  
```  
---
layout: faq
question: "eXperiencePoints (XP)  って何？"
---

# Q. eXperiencePoints (XP)  って何？  
みんなはBitcoinは知ってるよね？  
それと似たような仕組みの仮想通貨なんだ。  
仮想通貨は開発者が仕組みだけ作って、あとはその仕様に沿って増えていって勝手に流通する。  
日本円やアメリカドルみたいに管理されている法定通貨とは全く違うものなんだ。  
だから、誰かが欲しがれば価値は上がるし、みんないらないならゴミになっちゃうんだ。  
XPの開発チームは、みんなに使ってもらえるよう毎日がんばってるんだよ！  
```  
・レイアウト、一問一答の質問
```  
---
layout: faq
question: "eXperiencePoints (XP)  って何？"
---
```  
`question:`の内容がFAQの上部で列挙されます  

・質問内容  
```  
# Q. eXperiencePoints (XP)  って何？  
みんなはBitcoinは知ってるよね？  
それと似たような仕組みの仮想通貨なんだ。  
仮想通貨は開発者が仕組みだけ作って、あとはその仕様に沿って増えていって勝手に流通する。  
日本円やアメリカドルみたいに管理されている法定通貨とは全く違うものなんだ。  
だから、誰かが欲しがれば価値は上がるし、みんないらないならゴミになっちゃうんだ。  
XPの開発チームは、みんなに使ってもらえるよう毎日がんばってるんだよ！  
```  
質問内容は`#`で大きくしてます  
