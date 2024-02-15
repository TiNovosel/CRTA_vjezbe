# CRTA_vjezbe_01

Prva vježba upoznat će te s osnovnim komandama koje se u radu najviše koriste.

Vježba se sastoji od prvog commit-a na udaljeni repozitorij. 

### Zadatak

1. Koristite `git status` da vidite na kojoj ste grani.
2. Kako izgleda `git log`?
```sh
git status
git log
```
3. Kreirajte datoteku
```sh
touch ime_datoteke.txt
```
4. Kako sada izgleda izlaz iz `git status`?
```sh
git status
```
5. Dodajte datoteku u pripremni(stage) prostor
```sh
git add ime_datoteke.txt
```
6. Kako sada izgleda `git status`?
```sh
git status
```
7. `commit` datoteku u repozitorij 
```sh
git commit -m "objašnjenje commita"
git stash
```
8. Kako sada izgleda `git status`?
9. Promijenite sadržaj datoteke koju ste ranije kreirali
```sh
gedit ime_datoteke.txt
```
10. Koje su razlike i kako ih vidjeti?
```sh
git diff
```
11. Dodajte promjenu datoteke
```sh
git add ime_datoteke.txt
```
12. Kako sada izgleda `git status`?
13. Ponovno promijenite datoteku
14. Napravite `commit` 
15. Kako sada izgleda `status`? `Log`?
16. Dodajte i potvrdite najnoviju promjenu


Za `push` na udaljeni repozitorij potrebno je imati dozvolu i account poslužitelja na kojem se nalazi repozitorij, a za potrebe ove vježbe nadodane pormjene ćemo spremiti lokalno naredbom `stash`
```sh
git stash
```
