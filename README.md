EXcel VBAによる席替えアルゴリズム

「#VBA100本ノック 99本目」をお題に再帰を使った探索型の席替えアルゴリズムです。

現在の座席表に以下のような席番を割り振る。

 1   2   3   4   5   6 
 
 7   8   9  10  11  12 
 
13  14  15  16  17  18 

19  20  21  22  23  24 

25  26  27  18  29  30 

31  32  33  34  35  36 

全員が違う行列に移動、前後左右は現在と違う人という条件で席替えすると

 8  10   7   9  12  13 
 
 3   1   4   2  14   5 
 
 6  11  19  21  24  20 
 
15  18  16  31  34  17 

22  33  23  36  32  35 

29  25  28  26  30  27 
 
となる。
