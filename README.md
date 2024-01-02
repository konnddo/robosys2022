# robosys2023
ロボットシステム学の練習リポジトリ
[![test](https://github.com/konnddo/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/konnddo/robosys2023/actions/workflows/test.yml)

## 概要
標準入力から読み込んだ数字を足した結果，引いた結果，掛けた結果を表示する。

## インストール方法
```
git clone https://github.com/konnddo/robosys2023.git
cd robosys2023
```

## 使い方
```
$ seq x | ./plus
```
* xに整数を代入することで使用できる。

## 使用例
```
$ seq 1 | ./plus
1 -1 1
```
```
$ seq 5 | ./plus
15 -15 120 
```

## 必要なソフトウェア
* python

## テスト環境
* Ubuntu 22.04.2 LTS
* Python 3.7 ~ 3.10

## ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再配布および使用が許可されます.
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作ととしたものです.
    * [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* ©　2023　Mei Kondo
