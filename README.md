# Boyer-Moore algorithm heuristics

The main goal of this project is implementation of Boyer-Moore algorithm and heuristics comparison. Implemented herustics: 
- regular Boyer-Moore
- Zhu-Takaoka
- Smith 

[Video presentation](https://youtu.be/Qaw0Wh0lpXk)

## Content
- BoyerMooreHeuristics.ipynb - Jupyter notebook with source code
- Boyer-Moore algorithm heuristics.pptx - project presentation

## Assignment

Boyer-Moore algoritam koristi heuristike (Bad character and Good suffix rule) za preskakanje nepotrebnih poređenja karaktera pri pretraživanju. Definisati na sličan način dve heuristike (heuristika 1 i heuristika 2) koje mogu biti primenjivane za sračunavanje maksimalno dozvoljenog pomeraja. Za formiranje heuristika koristiti samo patern - algoritam treba da ostane on-line (10 poena).
Izvršiti merenje i poređenje vremena izvršavanja i memorijskog zauzeća seta on-line Exact Matching algoritama:
Boyer-Moore - Heuristika 1 + Heuristika 2
Boyer-Moore - Heuristika 1
Boyer-Moore - Heuristika 2
Boyer-Moore - Strong good suffix rule and bad character rule
Napisati wrapper funkciju ili klasu u programskom jeziku Python koja ima mogućnost izvršavanja zadate varijante algoritma na osnovu ulaznog parametra. Kao test podatke koristiti 3 seta podataka (5 poena):
Tekst: Coffea arabica, Chromosome 1c i paterni: ATGCATG, TCTCTCTA, TTCACTACTCTCA
Tekst: Mus pahari chromosome X, i paterni: ATGATG, CTCTCTA, TCACTACTCTCA
Genom po slobodnom izboru iz NIH baze i proizvoljna 3 paterna različite dužine.
Dobijene rezultate predstaviti tabelarno i grafički (Python matplotlib). Grafički način (dijagram) treba da bude dovoljno intuitivan da onaj koji ga čita može brzo izvući potrebne zaključke vezane za performanse zadatih varijanti algoritama (5 poena).
Za svaku od funkcija u kodu napisati testove (5 poena).
Pripremiti prezentaciju (Google slides ili power point) algoritama koji se testiraju, kao i samih rezultata (5 poena).
Pripremiti video prezentaciju projekta (3 - 5 minuta trajanja) koja će biti dostupna na YouTube ili drugom video servisu na kojem mu je moguće pristupiti (10 poena).
