# DCTC: materialele publice ale disciplinei

Disciplina *Dezvoltare colaborativă și tehnologii cloud* (DCTC), anul I, Matematică informatică și Informatică, Universitatea Tehnică din Cluj-Napoca, Centrul Universitar Nord din Baia Mare. Titular: conf. univ. dr. Cosmin Nicolae Sabo.

Acest depozit ține fișierele pe care le folosiți în proiectul echipei. Suportul de curs, fișele de laborator și testele sunt pe Campus Virtual.

| Ce | Pentru ce | Când |
| --- | --- | --- |
| [`raport-dctc.zip`](raport-dctc.zip) | șablonul raportului, gata de încărcat în Overleaf | laboratorul 4 |
| [`raport-dctc/`](raport-dctc/) | aceleași fișiere, de citit pe GitHub: `main.tex`, `refs.bib`, `figures/` | laboratorul 4 |
| [`notebooks/analiza-sablon.ipynb`](notebooks/analiza-sablon.ipynb) | notebook-ul șablon pentru temele 1–6: date dintr-un CSV, citit prin URL raw | laboratorul 5 |
| [`notebooks/explorare-sablon.ipynb`](notebooks/explorare-sablon.ipynb) | notebook-ul șablon pentru temele 7–10: date generate în notebook | laboratorul 5 |
| [`date-exemplu/`](date-exemplu/) | date sintetice, pe care rulează șablonul de analiză până când echipa își pune datele | laboratorul 5 |

## Raportul în Overleaf, din șablon

1. Descărcați [`raport-dctc.zip`](raport-dctc.zip): pe pagina fișierului, butonul *Download raw file*. Nu dezarhivați.
2. În Overleaf, pe pagina proiectelor: *New project* > *Existing project (.zip)*, apoi alegeți arhiva.
3. Proiectul se deschide cu `main.tex`, `refs.bib` și `figures/figura-exemplu.png`. *Recompile*: PDF-ul are două pagini, cu câmpurile de completat în roșu.
4. Redenumiți proiectul: `dctc-<numele-echipei>-raport`.

Compilatorul este pdfLaTeX (implicit în Overleaf). Ce înseamnă fiecare pachet și fiecare mediu din `main.tex` este explicat în suportul cursului 4; bibliografia (`refs.bib`, `\cite`, stilul `unsrtnat`), în suportul cursului 5.

## Notebook-urile în Colab

| Șablonul | Deschide în Colab |
| --- | --- |
| Analiza datelor echipei (temele 1–6) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cursuri-inf/DCTC/blob/main/notebooks/analiza-sablon.ipynb) |
| Explorarea numerică a temei (temele 7–10) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cursuri-inf/DCTC/blob/main/notebooks/explorare-sablon.ipynb) |

1. Butonul deschide șablonul în Colab; *File > Save a copy in Drive* face copia voastră, pe care lucrați.
2. *Runtime > Run all*: șablonul rulează în mai puțin de un minut pe planul gratuit.
3. Schimbați parametrii din secțiunea 1 și textele marcate „De completat”; la temele 1–6, `URL_DATE` devine adresa raw a fișierului din `data/` al depozitului echipei.
4. Notebook-ul se salvează în GitHub din Colab: *File > Save a copy in GitHub* (pentru un depozit privat, întâi *Tools > Settings > GitHub*, accesul la depozitele private).

În notebook nu intră parole, chei sau căi de pe calculatorul vostru.

## Licență

Șabloanele `raport-dctc` și `notebooks/` pot fi copiate și modificate liber, pentru proiectul disciplinei și pentru alte lucrări ([MIT](https://opensource.org/license/mit)). Datele din `date-exemplu/` sunt sintetice, sub [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
