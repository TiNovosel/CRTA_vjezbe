# CRTA_vjezbe_02: Praćenje i vraćanje promjena

1. Koji je sadržaj datoteke `file.txt`?
(snalaženje u VIM uređivaću teksta)
```sh
sudo apt install vim
vim file.txt
```
2. Prepišite sadržaj u `file.txt`:
kako biste promijenili stanje datoteke u radnom direktoriju
```sh
echo 2 > file.txt
```
3. Što nam govori `git diff`?
4. Što nam govori `git diff --staged`? Zašto je ovo prazno?


5. Dodajte svoje promjene iz radnog direktorija u `staged` promjene.
```sh
git add file.txt
```

6. Što nam govori `git diff`?
7. Što nam govori `git diff --staged`?

8. Prepišite sadržaj u `file.txt`:
kako biste promijenili stanje datoteke u radnom direktoriju
```sh
echo 3 > file.txt
```
9. Što nam govori `git diff`, a što `git diff --staged`?

11. Objasnite što se događa?

12. Pokrenite `git status` i primijetite da se `file.txt` pojavljuje dva puta u izlazu.

13. Pokrenite `restore` da vratite unazad promjene.
```sh
git restore --staged file.txt
```

14. Što sada govori `git status`?

15. `restore` promjene i napravite `commit`.

16. Kako izgleda log?
```sh
git log
```

17. Prepišite sadržaj u `file.txt`: `echo 4 > file.txt`

18. Koji je sadržaj datoteke `file.txt`?

19. Što nam govori `git status`?

20. Pokrenite `git restore file.txt`.

21. Koji je sadržaj datoteke `file.txt`?

22. Što nam govori `git status`?
