# Lecture 01 Basic Programmingその1

## 1-1. 四則演算と`print`関数の使い方

### 問題1-1-1 (src/p111.py)
- `print`関数を用いて、`src/p111.py`のファイルを実行すると`Hello World`が表示されるプログラムを実装せよ

### 問題1-1-2 (src/p112.py)
- `print`関数を用いて、`src/p112.py`のファイルを実行すると $4+4\times5$ の結果が表示されるプログラムを実装せよ

### 問題1-1-3 (src/p113.py)
- `print`関数を用いて、`src/p113.py`のファイルを実行すると $4-4^{5}$ の結果が表示されるプログラムを実装せよ

## 1-2. 変数と計算

### 問題1-2-1 (src/p121.py)
- まずは`src/p121.py`のファイルを実行し、計算結果を確かめよ
- その後、このプログラムファイルでは、`x, y, z`という変数を用いているが、変数名を自分の好きな名前に変更して実行すると同じ結果が出るようにプログラムを改良せよ

### 問題1-2-2 (src/p122.py)
- 変数`x`に1020を，`y`に3040を代入し，xとyの値の合計を表示するプログラムを`src/p122.py`に実装せよ

### 問題1-2-3 (src/p123.py)
- 変数`x`に1.5を代入し、xの値の1/10を表示するプログラムを`src/p123.py`に実装せよ

## 1-3. 入力関数input

### 問題1-3-1 (src/p131.py)
- `src/p131.py`は整数の入力をうながし，入力した数を表示するプログラムである。まずはこのプログラムを実行し、その挙動を確かめよ。
  - 特に、整数でない数値を入力するとプログラムエラーが起こることを確かめよ。また、どのようなエラー文が出力されているかについても精査すると良い。

- 次に、これをベースに、実行すると2つの整数を入力してその合計を表示するプログラムに改変せよ。以下は実装方針の例であるが、必ずしもこの通りでなくても良いものとする。
  
  1. 整数変数を2つ宣言する
  1. 整数を2つ入力し，宣言した変数に代入する
  1. 2つの整数の和を表示する

## 章末問題

### 問題1-4-1 (src/p141.py)
- 整数を2つ入力して，それらの積を表示し， さらに整数を2つ入力してそれらの積を表示し，最後に，今までに表示した2つの数の合計を表示するプログラムを`src/p141.py`を編集して実装せよ．
  - 例えば、プログラムを実行して10, 20, 33, 30を入力すると、以下のような実行結果になることが望ましい
  ```
  x1: 10
  x2: 20
  x1*x2 = 200
  x3: 33
  x4: 30
  x3*x4 = 990
  x1*x2 + x3*x4 = 1190
  ```

### 問題1-4-2 (src/p142.py)
- ある金額を入力すると、日本の通貨の仕組み（貨幣・紙幣）で金種別けを行った結果が出力されるプログラムを`src/p142.py`を編集して実装せよ。
  - 例えば、1986と入力すると以下のような出力が出力されることが望ましい
  ```
  10000円札: 0
  5000円札: 0
  1000円札: 1
  500円玉: 1
  100円玉: 4
  50円玉: 1
  10円玉: 3
  5円玉: 1
  1円玉: 1
  ```
