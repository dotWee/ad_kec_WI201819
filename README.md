# ad_kec_WI201819

Notizen, Anmerkungen und Lösungen zur Vorlesung Algorithmen und Datenstrukturen (AD/WI201718) in der Medizinischen Informatik (OTH/IM3) im Wintersemester 2018/19

## Übungsaufgaben

Folgende Aufgaben wurden bearbeitet und sind sortiert nach Blatt/Aufgabe im Unterordner [Übungen](/uebungen) zu finden:

- [x] [Übungsblatt 1](/uebungen/blatt_01/) (_Abgabe bis 08.10.2018_)
  - [x] [Aufgabe 1](/uebungen/blatt_01/aufgabe_01/) (Euklidischer Algorithmus)
  - [x] [Aufgabe 2](/uebungen/blatt_01/aufgabe_02/) (Abstrakter Datentyp)
  - [x] [Aufgabe 3](/uebungen/blatt_01/aufgabe_03/) (Abstrakter Datentyp)
  - [x] [Aufgabe 4](/uebungen/blatt_01/aufgabe_04/) (Aufwandsberechnung)

    Notiz: Teilaufgabe 4b) wurde nicht bearbeitet, da Ergebnisse von 4a) möglicherweise fehlerhaft sind.

- [ ] Übungsblatt 2
  - [ ] [Aufgabe 1](/uebungen/blatt_02/aufgabe_01/) (Registermaschinensimulator)
  - [ ] [Aufgabe 2](/uebungen/blatt_02/aufgabe_02/) (O-Notation)
  - [ ] [Aufgabe 3](/uebungen/blatt_02/aufgabe_03/) (O-Notation)
  - [ ] [Aufgabe 4](/uebungen/blatt_02/aufgabe_04/) (Implementierung einer Funktion)

- [ ] Übungsblatt 3
  - [ ] [Aufgabe 1](/uebungen/blatt_03/aufgabe_01/) (Fibonacci-Zahlen)
  - [ ] [Aufgabe 2](/uebungen/blatt_03/aufgabe_02/) (Iterations- und Substitutionsmethode)
  - [ ] [Aufgabe 3](/uebungen/blatt_03/aufgabe_03/) (Master-Methode)
  - [ ] [Aufgabe 4](/uebungen/blatt_03/aufgabe_04/) (Algorithmenimplementierung)

- [ ] Übungsblatt 4
  - [x] [Aufgabe 1](/uebungen/blatt_04/aufgabe_01/) (Implementierung von Sortieralgorithmen)
  - [x] [Aufgabe 2](/uebungen/blatt_04/aufgabe_02/) (Anpassen von Sortieralgorithmen)
  - [ ] [Aufgabe 3](/uebungen/blatt_04/aufgabe_03/) (Anwendung von Sortieralgorithmen)
  - [ ] [Aufgabe 4](/uebungen/blatt_04/aufgabe_04/) (Iterativ vs rekursiv)

- [ ] Übungsblatt 5
  - [x] [Aufgabe 1](/uebungen/blatt_05/aufgabe_01/) (MergeSort und HeapSort)
  - [x] [Aufgabe 2](/uebungen/blatt_05/aufgabe_02/) (Implementierung eines Algorithmus)
  - [ ] [Aufgabe 3](/uebungen/blatt_05/aufgabe_03/) (Heaps)
  - [ ] [Aufgabe 4](/uebungen/blatt_05/aufgabe_04/) (Matrixprodukt)

- [ ] Übungsblatt 6
  - [x] [Aufgabe 1](/uebungen/blatt_06/aufgabe_01/) (Quicksort)
  - [x] [Aufgabe 2](/uebungen/blatt_06/aufgabe_02/) (Matrixprodukt)
  - [x] [Aufgabe 3](/uebungen/blatt_06/aufgabe_03/) (Countsort, Heapsort, Mapsort)
  - [ ] [Aufgabe 4](/uebungen/blatt_06/aufgabe_04/) (Binäre, verkettete Bäume)

- [ ] Übungsblatt 7
  - [x] [Aufgabe 1](/uebungen/blatt_07/aufgabe_01/) (Binäre, verkettete Suchbäume)
  - [ ] [Aufgabe 2](/uebungen/blatt_07/aufgabe_02/) (AVL-Bäume)
  - [ ] [Aufgabe 3](/uebungen/blatt_07/aufgabe_03/) (AVL-Bäume)
  - [ ] [Aufgabe 4](/uebungen/blatt_07/aufgabe_04/) (Sortieren mithilfe von AVL-Bäumen)

## Markdown2pdf

Installieren:

```bash
$ npm install -g markdown-pdf
...
```

Alle Markdowns in Unterordnern rendern:

```bash
$ for readme in `find . -name '*.md'`; do markdown-pdf $readme -o $(echo $readme | sed 's/README.md/Abgabe.pdf/g'); done
...
```