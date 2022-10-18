---
title: "指定轉乘站"
categories:
  - Blog
tags:
  - user-guide
  - transfers
excerpt: |
  如何使用「指定轉乘站」功能使路徑規劃結果更符合需求
header:
  overlay_image: /assets/images/bay_platform.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo by [**Michał Parzuchowski**](https://unsplash.com/@mparzuchowski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [**Unsplash**](https://unsplash.com/s/photos/train-station?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)"  
---


TransTaiwan於Android 1.4.0版/iOS 1.2.0版加入了「指定轉乘站」功能，以彌補路徑規劃在一些狀況中產生不如預期的結果。
「指定轉乘站」運作方式類似於設置一個中繼點，進而規劃出一定會通過這個中繼點的行程。但是，單純的設定轉乘站有時仍無法達到預期的需求，因此，以下將以一個例子說明如何設置「指定轉乘站」能有較佳效果。<br><br>

## 範例: 台鐵桃園站 -> 高鐵嘉義站 希望於新烏日轉乘高鐵

在這個例子中，路徑規劃會以板橋為轉乘站，如下圖。

![](/assets/images/specify_via_1.jpg)

這時，就可以使用「指定轉乘站」，來規劃出經由新烏日轉乘的路徑。
但是，若單純將轉乘站設定於新烏日，仍會規劃出一樣的結果，因為**原本的路徑就有經過新烏日**。<br>

此時，可以將指定轉乘站設定於**豐原站**，就能規劃出經由新烏日轉乘高鐵的路徑，如下圖。

![](/assets/images/specify_via_2.jpg)

## 總結

因為演算法的限制，在許多狀況中，「指定轉乘站」的設置需要有一些技巧。若原本的設置中規劃結果仍不合預期，可以試著將轉乘站設置在希望經過的路段中間，而非直接設在轉乘點上，以免因為原本的規畫結果就已經有經過該車站而效果不佳。
