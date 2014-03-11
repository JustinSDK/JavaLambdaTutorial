Java Lambda Tutorial
====================

![Java Lambda Tutorial](cover.jpg)

你可以在 [Google Play](https://play.google.com/store/books/details?id=iwvMAgAAQBAJ) 或 [Pubu](http://www.pubu.com.tw/ebook/Java-Lambda-Tutorial-29189) 上取得 PDF 與 ePub 格式的電子書。

相對於 JavaScript、Python、Scala 等本身支援一級函式（First class function）的語言，Java 開發者對於一級函式是比較陌生的，因而在 2010 年 JCD 中的議程 [Lambda/Closure - 從 JavaScript、Python、Scala 到 Java SE 7](http://www.slideshare.net/JustinSDK/lambdaclosure-javascriptpythonscala-java-se-7 "Lambda/Closure - 從 JavaScript、Python、Scala 到 Java SE 7")，我簡單地從 JavaScript、Python、Scala 等語言的一級函式特性開始介紹，分享了 Java 要加入 Lambda/Closure 會有什麼樣的考量。

Java 的 Lambda 語法後來歷經了數次的討論與改變，後來確定在 Java SE 8 中引入 Lambda，也引進了因應新語法而帶來的 API 新功能，因而我在 2012 年 Java TWO 議程 [Java SE 8 的 Lambda 連鎖反應](http://www.slideshare.net/JustinSDK/java-se-8-lambda "Java SE 8 的 Lambda 連鎖反應") 中，從 Lambda 演算開始探討了 Lambda 的前世今生，以及會對 Java 帶來的新典範（Paradigm）與風格。

Java 引入的新典範其實有著函數式程式設計（Functional programming）的影子，想要善用 Java 引入的 Lambda 語法與新 API，先認識函數式程式設計會有非常大的幫助，因而在 2012 年 JCD 中，我於議程 [Java 開發者的函數式程式設計](http://www.slideshare.net/JustinSDK/java-16416534 "Java 開發者的函數式程式設計") 中探討了函數式程式設計，以及在 Java 中如何適當地運用函數式風格。

Java SE 8 確定於 2014 年 3 月發表，而我發現過去的這幾個議程可以整理成為系列文章，讓大家可以認識 Java 中 Lambda 的前世今生。除此之外，最後並加上了 JDK8 Functional API 的介紹，讓本書對 JDK8 Lambda 的介紹更為完整。

- 認識 Lambda/Closure
  - [從 JavaScript 的函式物件談起](http://www.codedata.com.tw/java/understanding-lambda-closure-1-from-javascript-function-1)
  - [什麼是 Closure？](http://www.codedata.com.tw/java/understanding-lambda-closure-2-what-is-closure-2)
  - [Python 對 Lambda/Closure 的支援](http://www.codedata.com.tw/java/understanding-lambda-closure-3-python-support/)
  - [從 Scala 中借鏡](http://www.codedata.com.tw/java/understanding-lambda-closure-4-learning-from-scala-lang/)
  - [Java 的稻草人提案](http://www.codedata.com.tw/java/understanding-lambda-closure-5-straw-man/)
  - [一級函式與 Lambda 演算](http://www.codedata.com.tw/java/understanding-lambda-closure-6-lambda-calculus/)
  - [JDK8 Lambda 語法](http://www.codedata.com.tw/java/understanding-lambda-closure-7-jdk8-lambda-syntax/)
  - [方法參考與建構式參考](http://www.codedata.com.tw/java/understanding-lambda-closure-8-method-constructor-reference/)

- Java 開發者的函數式程式設計
  - [初探函數式程式設計](http://www.codedata.com.tw/java/functional-programming-for-java-developers-1-a-preliminary-study/)
  - [代數資料型態](http://www.codedata.com.tw/java/functional-programming-for-java-developers-2-algebraic-data-types/)
  - [List 處理模式](http://www.codedata.com.tw/java/functional-programming-for-java-developers-3-list-patterns/)
  - [不可變特性](http://www.codedata.com.tw/java/functional-programming-for-java-developers-4-immutability/)
  - [JDK8 預設方法](http://www.codedata.com.tw/java/functional-programming-for-java-developers-5-jdk8-default-methods/)
  - [惰性](http://www.codedata.com.tw/java/functional-programming-for-java-developers-6-laziness/)
  
- JDK8 Functional API
  - [使用 Optional 取代 null](http://openhome.cc/Gossip/Java/Optional.html)
  - [Consumer、Function、Predicate 與 Supplier](http://openhome.cc/Gossip/Java/ConsumerFunctionPredicateSupplier.html)
  - [使用 Stream 進行管線操作](http://openhome.cc/Gossip/Java/Stream.html)
  - [Stream 的 reduce 與 collect](http://openhome.cc/Gossip/Java/Reduction.html)
  - [Optional 與 Stream 的 flatMap](http://openhome.cc/Gossip/Java/FlatMap.html)
  - [Stream 與平行化](http://openhome.cc/Gossip/Java/ParallelStream.html)


