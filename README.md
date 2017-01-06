# fi.py-code
経済指標から今後の株価を予想する


## 概要

Tensorflowを用いてYahoo Financeのデータから株予想をする

***DEMO:***

![SCS](http://imgur.com/a/QLw87 "サンプル")

## 機能


https://finance.yahoo.com/quote/%5EN225?ltr=1  からデータを取得し、株価の上下予測を百分率で表す
 


## 環境  

Python3  
Tensorflow 0.12.1
numpy 1.11.3
pandas
Ubuntu16.04  

## 使用の流れ

1. git からインストール
2. 端末で "fi.py" を実行
3~ INDEX_LISTの指標データは任意に変える
   
## インストール

    $ git clone https://github.com/ryusato2/fi.py-code


## その他

・INDEX_LISTに南アフリカ、インドネシア、ニュージーランドのデータも入れてみると面白いかも  
・隠れ層を増やしてみたところPredictionが落ちた...原因は入力データに統一性がないからだろうか  



