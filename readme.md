# PVA2 - Programování a vývoj aplikací
## Cvičení 09: Opakování Funkce a cykly

### 1
Deklarujte funkce `multiplication`. Úkolem funkce bude postupné vypsání  1-10 násobku daného čísla.

Například pro atribut 2 bude výstup
```
2
4
6
8
10
12
14
16
18
20
```

### 2
Napište program `row` s využitím dvou cyklů. Budete vypisovat postupně od čísla 0 do hodnoty a zpátky do 0.
Vstupní parametr bude obsahovat maximální hodnotu výpisu.
Aby se hodnoty vypsaly na jednom řádku, využijte `end=' '` jako další atribut fce print
Výstup fce naformátujte dle vzoru

```
Ukázka výstupu fce pro atribut 10:
0 1 2 3 4 5 6 7 8 9 10 9 8 7 6 5 4 3 2 1 0
``` 

``` 
Řada čísel tam a zpátky pro hodnotu 10 je: 0 1 2 3 4 5 6 7 8 9 10 9 8 7 6 5 4 3 2 1 0
``` 




### 3
Za využití cyklu zobrazte hodnoty seznamu v opačném pořadí. Název funkce reverse.

`list1 = [10, 20, 30, 40, 50, 60, 70, 80, 90]`
```
Očekávaný výstup: 
90
80
70
60
50
40
30
20
10
```

### 4
Zkopírujte si kód z předchozího cvičení a funkci přejmenujte na reverseList. Za využití cyklu bude funkce vracet seznam, který bude mít hodnoty opačném pořadí.

### 5
Deklarujte funkci `removeFromList`, která bude vracet upravený seznam. Fce odstraní ze seznamu všechny hodnoty zadané uživatelem. Seznam a hodnota k odstranění budou zadávány jako parametr funkce



### 6
V souboru createList.py vytvořte program pro naplnění seznamu.

* Program se zeptá uživatele kolik hodnot bude chtít zadat.
* Následně uživatel zadá všechny hodnoty. Při zadávání zobrazte uživateli zprávu ve tvaru: 
```
Zadej 1. prvek z 5:
 ```
* Zadané hodnoty mohou být pouze kladné. Při záporné hodnotě požádejte uživatele o nový vstup.
```
Zadej 1. prvek z 3: -8
Nepodporovaná hodnota, zadej znovu
Zadej 1. prvek z 3: 8
```
* Po úplném naplnění seznamu zobrazte uživateli zadané hodnoty.

### 7

V souboru `game.py` vytvořte hru pro hádání čísel.
* Od uživatele si vyžádejte dvě hodnoty rozsahu.
* Program vygeneruje náhodné číslo v zadaném rozsahu.
* Vy jako uživatel budete hádat hodnotu. Každou odpověď program vyhodnotí a řekne vám, jestli zadaná hodnota je menší nebo větší.
* Jako bonus pokud uživatel zadá hodnotu `-1`, ukončete hádání a napište uživateli informaci o prohře a jaké bylo hledané číslo.
