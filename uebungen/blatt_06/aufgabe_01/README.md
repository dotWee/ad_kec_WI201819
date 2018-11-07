# Aufgabe 01 (Quicksort)

## a)

Der Quellcode zur Implementierung in C++ kann in [verketteteliste.cpp](verketteteliste.cpp) eingesehen werden und mit _make_ ausgeführt werden.

    Notiz: Eine Implementierung des Quicksort Algorithmus zum Sortieren der Liste ist (noch) nicht vorhanden.

```bash
$ make verketteteliste
clang++ verketteteliste.cpp -o Verketteteliste
chmod +x Verketteteliste
./Verketteteliste
Zahl eingeben (0 für Ende)
6
Zahl eingeben (0 für Ende)
2
Zahl eingeben (0 für Ende)
9
Zahl eingeben (0 für Ende)
5
Zahl eingeben (0 für Ende)
3
Zahl eingeben (0 für Ende)
0
3
5
9
2
6
```

## b)

Der Quellcode zur Implementierung in C++ kann in [Lotto.cpp](Lotto.cpp) sowie [Ringliste.h](Ringliste.h) und [Ringliste.cpp](Ringliste.cpp) eingesehen werden. _Make_ wird zur Ausführung genutzt:

```bash
$ make lotto
clang++ -c Lotto.cpp
clang++ -c Ringliste.cpp
clang++ Lotto.o Ringliste.o -o Lotto
chmod +x Lotto
./Lotto
Starte nach dem 31. Element
1. Zahl:  position=31 wert=31
2. Zahl:  position=37 wert=37
3. Zahl:  position=43 wert=43
4. Zahl:  position=49 wert=49
5. Zahl:  position=55 wert=5
6. Zahl:  position=61 wert=11
```