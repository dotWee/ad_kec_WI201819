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

- [ ] Übungsblatt 5
  - [x] [Aufgabe 1](/Übungen/Blatt_05/Aufgabe_01/) (MergeSort und HeapSort)
  - [ ] [Aufgabe 2](/Übungen/Blatt_05/Aufgabe_02/) (Implementierung eines Algorithmus)
  - [ ] [Aufgabe 3](/Übungen/Blatt_05/Aufgabe_03/) (Heaps)
  - [ ] [Aufgabe 4](/Übungen/Blatt_05/Aufgabe_04/) (Matrixprodukt)

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