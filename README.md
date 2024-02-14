# CRTA_vjezbe: Osnovne grananja

S granama smo se već susreli 

1. Koristite `git branch` da vidite sve dostupne grane
2. Na kojoj se grani trenutno nalazite?
3. Koristite `git branch ime_grane` da stvorite novu granu pod nazivom `moja_grana`
```sh
git branch moja_grana
```
4. Ponovno koristite `git branch` da vidite novostvorenu granu.
5. Koristite `git switch moja_grana` da se prebacite na vašu novu granu.
```sh
git switch -c moja_grana
```
6. Kako se mijenja izlaz iz `git status` kada se prebacujete između `04_vjezbe` grane i nove grane koju ste stvorili?
7. Kako se radni direktorij mijenja kada se mijenjate između dvije grane?
8. Provjerite jeste li na grani `moja_grana` prije nego što nastavite.
9. Stvorite datoteku pod nazivom `skripta.py` s vašim imenom.
```sh
touch skripta.py
```
10. Dodajte datoteku i napravite `commit` s tom promjenom.
```sh
git add skripta.py
git commit -m "dodajem moju skriptu na udaljeni repozitorij"
```
11. Koristite `git log --oneline --graph` da vidite vašu granu koja pokazuje na novi commit.
12. Vratite se na granu nazvanu `04_vjezba`.
```sh
git checkout 04_vjezba
```
Istražiu koja je razlika između `git switch` i `git checkout`?

13. Koristite `git log --oneline --graph` i primijetite kako commit koji ste napravili na grani `moja_grana` nedostaje na grani `04_vjezba`.
14. Napravite novu datoteku pod nazivom `tekst.txt` i commitajte tu datoteku.
15. Koristite `git log --oneline --graph --all` da vidite vašu granu koja pokazuje na novi commit, i da sada dvije grane imaju različite commite na njima.
16. Prebacite se na vašu granu `moja_grana`.
17. Što se dogodilo s vašim radnim direktorijem? Možete li vidjeti vašu `tekst.txt`?
18. Koristite `git diff moja_grana 04_vjezba` da vidite razlike između dvije grane.
