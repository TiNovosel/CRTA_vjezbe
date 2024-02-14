# CRTA_vjezbe_03: Istraživanje

Glavno pitanje ove vježbe je gdje se bilježe pojedinosti o repozitoriju?

Za bolji prikaz datoteka i foldera instaliravamo paket `tree`
```sh
sudo apt install tree
```

Pogledaj datoteke u folderu:
```sh
ls
```
Kako točka na početku naziva foldera predstavlja skriveni folder s osnovnom naredbom `ls` nismo u mogućnosti uočiti skrivene foldere. Probaj:
```sh
ls -a
```
ili još bolje 
```sh
ls -la
```

Primjećujemo mapu pod nazivom `.git` i ulazimo u mapu:
```sh
cd .git
```

Prethodno instaliranim paketom pregledavamo sadržaj mape:
```sh
tree
```

### .git mapa

`.git` mapa je skriveni direktorij u projektu kojim upravlja Git i sadrži sve potrebne metapodatke i objekte za konfiguraciju verzioniranja. Ova mapa se stvara u korijenskom direktoriju vašeg projekta kada pokrenete naredbu `git init`, kojom se inicijalizira novi Git repozitorij.

Evo detaljnog pregleda na pojedine datoteke i foldere koji se obično nalaze unutar `.git` mape:

1. **config** - Ova datoteka sadrži postavke specifične za repozitorij, uključujući lokacije udaljenih repozitorija, informacije o granama i druge preferencije.

```sh
cat config
```

2. **HEAD** - Referenca na trenutnu granu ili commit koji je izvadan.


```sh
cat HEAD
```

3. **objects/** - Ovaj direktorij pohranjuje sav sadržaj vašeg repozitorija, uključujući svaku verziju svake datoteke i mape. Organiziran je kao sustav za pohranu adresiranih sadržaja, pohranjujući datoteke po njihovom SHA-1 hashu.

4. **logs/** - Ova mapa sadrži zapise logova promjena u refs (kao što su heads i tags). Datoteka `logs/HEAD` bilježi promjene u HEAD.


Razumijevanje mape `.git` obično nije potrebno za osnovne operacije s Gitom, jer Git apstrahira složenost verzioniranja. 
