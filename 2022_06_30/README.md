# 2022/6/30 C++ 練習題
## a693: 吞食天地
Content
好餓歐歐歐歐

有 n 個食物在你面前排成一排

每個食物有它的飽足度

你想知道把其中一段通通吃掉會獲得多少飽足度

Input
多組測資以 EOF 結束

每組測資開始有兩個正整數 n,m (n,m <= 100000)

接下來一行有 n 個不超過一千的正整數依序代表每個食物的飽足度

接下來 m 行每行有兩個數字 l,r (1 <= l <= r <= n)

代表你想要吃掉第 l 個到第 r 個食物 

Output
對每組測資輸出 m 行，代表總飽足度
```
Sample Input #1
3 3
1 2 3
1 3
1 2
2 3
Sample Output #1
6
3
5
```
## d478: 共同的數 - 簡易版
Content
因為學長覺得d136太可怕，所以出一題簡單版的XD 

小潘跟小花都有很多個正整數，自己的數不會有重覆出現的，而且都是遞增排列。

現在她們想要知道，兩個人的數有幾個重覆的呢？

Input
第一行有兩個數字n,m。 (1<=n<=100,1<=m<=10000)

接著共有n筆測資，每筆測資共有兩行，分別代表兩個人擁有的數，每行共有m個數。

所有數字都不大於231-1。

Output
每筆測資請輸出一個數字，

代表兩個人的數有幾個重覆的。
```
Sample Input #1
2 6
1 5 6 8 9 13
3 4 5 7 8 11
4 6 7 14 16 23
6 9 12 13 16 23
Sample Output #1
2
3
```
## d673: 11608 - No Problem
Content
最近程式競賽非常頻繁。儘管對參賽者來說這是好事，對出題者來說卻適得其反。目前出題者尚能維持一個題庫並說：「沒有問題！」但是如果繼續這樣下去不知道還能維持多久。

給你一年中每個月所出的題目數量及每個月所需要的題目數量。如果某個月需要 N 個題目，而當時的題庫數量不足，那麼該月的所有比賽均取消。請寫個程式來判斷是否有足夠的題目來辦比賽。記住，如果某個題目是在 X 月出的，該題目必須在 X+1 月或其後的月份才能使用。

Input
每筆測資的第一行有一個整數 S (0≤S≤100)，表示年初已有的庫存題目數量。第二行有 12 個以空白隔開的整數，依序表示一到十二月每個月所出的題目數量。第三行也有 12 個以空白隔開的整數，依序表示每個月比賽所需要的題目數量。這些整數會介於 0 到 20 之間 (含)。負數代表輸入的結束。
Output
對於每筆測資，印出一行 "Case X:"，X 代表測資編號。然後印出 12 行，如果 i 月 (1≤i≤12) 有足夠的題目，則在第 i 行印出 "No problem! :D" (沒有問題)，否則印出 "No problem. :(" (沒有題目)。
```
Sample Input #1
5
3 0 3 5 8 2 1 0 3 5 6 9
0 0 10 2 6 4 1 0 1 1 2 2
-1
Sample Output #1
Case 1:
No problem! :D
No problem! :D
No problem. :(
No problem! :D
No problem! :D
No problem! :D
No problem! :D
No problem! :D
No problem! :D
No problem! :D
No problem! :D
No problem! :D
```
## e998: Snake
Content
Snake矩陣是形狀恰似一條蛇的矩陣。

例如：

1 2 3

6 5 4

7 8 9

現在給你邊長，請你輸出整個矩陣

Input
多筆測資

每行有正整數n，n不大於100。

Output
輸出一個n*n的Snake矩陣(如範例)

不同測資記得空一行
```
Sample Input #1
3
4
Sample Output #1
1 2 3 
6 5 4 
7 8 9 

1 2 3 4 
8 7 6 5 
9 10 11 12 
16 15 14 13 
```