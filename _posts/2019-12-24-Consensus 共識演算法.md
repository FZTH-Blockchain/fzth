---
layout: post 
current: post
cover: assets/images/panda-59.png #封面圖片
navigation: True #上方導覽列
title: Consensus 共識演算法 #id-標題名稱
date: 2019-12-24 #日期 YYYY-MM-DD 
tags: blockchain #標籤
class: post-template 
subclass: 'post' 
author: panda #作者 
---
> 大家都知道區塊鏈的核心圍繞在「共識」上。那跟我們日常生活有什麼不同呢？基本上，我們生活中無時無刻都是在維持「共識」，該怎麼說呢？那就讓我們看下去吧！

- 古時候，雙方取得**共識**便可以交換商品。
- 現代，雙方取得**共識**便可以購買商品。

倘若你不相信對方呢？那就會透過「公正第三方」來當作彼此的橋樑。

> 區塊鏈中也當然存在著共識，我們用大家最常見的拜占庭將軍簡化版來給大家了解一下。


## 角色介紹

從前從前有兩位將軍

<div align="center">
    <img src="https://i.imgur.com/pBivxBf.png">
</div>


### 將軍問題

- 單一將軍是無法打贏敵人的。
- A 將軍必須在敵方營地派遣一個使者，將進攻時間傳給 B 將軍。（ B 將軍將使者送給 A 將軍）。
- 這個使者有可能在路上發生意外或被敵軍抓走。
- 使者在回傳訊息時，也有可能發生上述的問題。

<div align="center">
    <img src="https://i.imgur.com/lsc2Tsg.png">
</div>

<br>

<div align="center">
    <img src="https://i.imgur.com/lxlLPpj.png">
</div>

### 拜占庭將軍問題

- 它描述了相同的場景，在這個場景中，需要兩名以上的將軍商定時間攻擊他們的共同敵人。
- 這是一個或多個將軍可以成為叛徒，這意味著他們可以為自己的選擇撒謊。
- 設置簡單命令，攻擊或後退。

<div align="center">
    <img src="https://i.imgur.com/QMcBvTq.png">
</div>

<br>

<div align="center">
    <img src="https://i.imgur.com/LQKjx11.png">
</div>

-----


> 區塊鏈使用共識算法選出一個領導者，該領導者將決定下一個區塊的內容。



-----
## POW 


為了被選為領導者並選擇要添加到區塊鏈的下一個區塊，他們必須找到特定數學問題的解決方案。
為該問題提供解決方案後，很容易驗證它是否正確。

![https://ithelp.ithome.com.tw/upload/images/20191014/201183257dSCt7loGw.png](https://ithelp.ithome.com.tw/upload/images/20191014/201183257dSCt7loGw.png)

## POS 

權益證明（Proof-Of-Stake, PoS）是在區塊鏈公鏈中的共識機制，它的出現，主要是希望取代工作量證明，從而減少為了產生新區塊而進行「挖礦」的大量運算。它與工作量證明 Proof-Of-Work 不同的是：在 PoW 中，大家比拼的是「算力」（運算能力），通過大量運算得出符合難度的 Hash 值，從而得到獎勵，亦無法預期是由誰產生下一個區塊；而在 PoS ，大家比拼的是「權益」，「權益」越大的人越大機會負責產生新區塊，也就是說能夠預期是由誰產生下一個區塊，所以 PoW 與 PoS 之間對於產生新區塊的方式存在很大差異，而且由於 PoW 的「挖礦」過程需要消耗龐大電力，造成對環境的破壞。而 PoS 的出現則試圖以另一種不同的機制取代「挖礦」來解決這個問題。

![https://ithelp.ithome.com.tw/upload/images/20191014/20118325S6ba9bKJ0j.png](https://ithelp.ithome.com.tw/upload/images/20191014/20118325S6ba9bKJ0j.png)

## 小結

今天聊聊簡易版的共識，讓大家看完上一篇的分岔，就可以來聊聊共識～
這些東西是十分有趣的，而且以太坊現在也要從 POW -> POS ! 

若文章有任何的問題或要討論的部分，歡迎透過以下方式聯繫我。

- [Facebook](https://www.facebook.com/fzthblockchain) 
- Email: (pandap.d819@gamil.com)
- [Slack](https://join.slack.com/t/fzth/shared_invite/enQtODQxMDQxMjE5MDU4LWJlZGNmZGNmODZiNzE3OWIyYTVjOTZhYjhiMjdlOWY0NGY5OTNjMzA0YTNlMmU2OGZlZTU3NzUzZTdiZTgxNTE)