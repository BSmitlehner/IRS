### ASCII i kodne stranice

> Vrijednos ASCII znaka kao takva se ne zapisuje u memoriju

**Pretvorba znaka u Unicode:**

> d:U-0064

+ Schema kodiranja u Unicodu po 1. bajtu 

$\fbox{0,x,x,x,x,x,x,x}$ $\leftarrow$ Unicode 1.Byte

U binarnom zapisu(iz hexa) 0064 je: 0000 0000 0110 0100

Makni prednje vrijednosti do 0000 0000 0(ostaje $\fbox{1,0,0,0,1,0,0}$) i dodaj nulu na osmo mjesto 

Finalni rezultat $\rightarrow$ 0100 0100

**PRETVORBA ISTIM KORACIMA U SUPROTNOM SMJERU ZA DEKODIRANJE UNICODA U BROJ!!!**


| Unicode | Byte1 | Byte 2|
|-----------|--------------|-------------|
|U+0000 - U007F|0xxxxxxx|
|U*0080 - U+07FF|110yyyxx|10xxxxxx|

**y = prva dva bajta,**
**x = druga dva bajta**

Na broju 1100 0100 1000 1101:

1100 0100 $\leftarrow$ svaki je svoj y po vrijednostima (ispod svakog zamišljeni y)

1000 1101 $\leftarrow$ svaki je x po svojim vrijednostima (ispod svakog je zamišljeni x)

---

#### Pretvorba s pomičnim zarezom

>12.625

12,625$(16)$ = 1100,101$(2)$


Normalizacija 1100,101 u oblik **1,f**

Makni zarez lijevo do 1,100101

Nakon toga 1,100101 x 2^3 

eksponent se zapiše u binarnom zapisu u jedan byte (3 = 0000011)

00000011 1001010 00000000 0000000 po bytu je jedna riječ:prvi byte je eksponent pa je mantisa dva bytea pa puni s nulama zadnji.


$\fbox{100000011,10010100,0000000,00000000}$ $\leftarrow$ 81CA0000$(16)$
