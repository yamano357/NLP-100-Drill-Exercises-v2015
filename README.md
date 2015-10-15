# NLP-100knock-v2015

---

## 前書き（言語処理100本ノックについて）  
- 本稿では、東北大学の乾・岡崎研究室で公開されている[言語処理100本ノック（2015年版）](http://www.cl.ecei.tohoku.ac.jp/nlp100/)を、R言語で解いていきます。  
- [改訂前の言語処理100本ノック](http://www.cl.ecei.tohoku.ac.jp/index.php?NLP%20100%20Drill%20Exercises)も同様に上記研究室のサイトにあります。

## 前書き（Rに関して）  
- Rの構文や関数についての説明は一切ありませんので、あらかじめご了承ください。  
- 本稿では、{base}にある文字列処理ではなく、{stringr}（1.0.0以上）とパイプ処理を極力用いております（{stringi}も処理に応じて活用していきます）。課題によってはパイプ処理でこなすのに向かない状況もありますので、あらかじめご了承ください。
- Rのコーディングスタイルには下記を使用しております。  
　[Rのコーディングルールについて](http://rpubs.com/yamano357/85463)  

- パイプ処理でのRの書き方は、下記のページなどをご参考ください。  
-- {dplyr}
　[hadley/dplyr](https://github.com/hadley/dplyr)  
　[大規模データの高速処理 ーdata.table、dplyrー](http://kohske.github.io/ESTRELA/201410/index.html)  
　[dplyrを使いこなす！基礎編](http://qiita.com/matsuou1/items/e995da273e3108e2338e)  
　[dplyrを使いこなす！Window関数編](http://qiita.com/matsuou1/items/db6e8c48fcfd791dd876)  
　[dplyrを使いこなす！JOIN編](http://qiita.com/matsuou1/items/b1bd9778610e3a586e71)  
　[Non-standard evaluation](https://cran.r-project.org/web/packages/dplyr/vignettes/nse.html)  
　[NSEとは何か](http://qiita.com/kohske/items/7dbef6ae3ff34c093ce4)  
-- {tidyr}  
　[hadley/tidyr](https://github.com/hadley/tidyr)  
　[{tidyr}でよく使う関数のメモ](https://rpubs.com/kazutan/tidyr_memo)  
-- {stringr}と{stringi}  
　[hadley/stringr](https://github.com/hadley/stringr)  
　[RPubs - このパッケージがすごい2014: stringr](https://rpubs.com/uri-sy/demo_stringr)  
　[stringiで輝く☆テキストショリスト](http://qiita.com/kohske/items/85d49da04571e9055c44)  
　[stringr 1.0.0を使ってみる](http://notchained.hatenablog.com/entry/2015/05/01/011703)  
　[{stringr}/{stringi}とbaseの文字列処理について](http://rpubs.com/yamano357/92478)  
-- {readr}  
　[hadley/readr](https://github.com/hadley/readr)  
　[readr とは？](http://oku.edu.mie-u.ac.jp/~okumura/stat/readr.html)  
　[readr 0.0.0.9000を使ってみる](http://notchained.hatenablog.com/entry/2015/03/22/150827)  

---

## 公開先のrPubsページ  
- [第1章:準備運動](http://rpubs.com/yamano357/84965)  
- [第2章:UNIXコマンドの基礎](http://rpubs.com/yamano357/85313)  
- [第3章:正規表現](http://rpubs.com/yamano357/86911)  
- [第4章:形態素解析](http://rpubs.com/yamano357/90200)  
- [第5章:構文解析](http://rpubs.com/yamano357/91770)  
- [第6章:英語テキストの処理](http://rpubs.com/yamano357/94986)  
- [第7章:データベース](http://rpubs.com/yamano357/98624)  
- [第8章:機械学習](http://rpubs.com/yamano357/100016)  
- [第9章:ベクトル空間法 (I)](http://rpubs.com/yamano357/107149)  
- [第10章:ベクトル空間法 (Ⅱ)](http://rpubs.com/yamano357/117496)  

## まとめ記事  
- [Rによる言語処理100本ノック前半まとめ](http://yamano357.hatenadiary.com/entry/2015/07/27/001728)  
- [第50回R勉強会＠東京(TokyoR)にてLT発表しました](http://yamano357.hatenadiary.com/entry/2015/09/08/231844)  
- [第4回「NLP勉強会」を開催しました #NLPStudy](http://yamano357.hatenadiary.com/entry/2015/10/04/190946)  

