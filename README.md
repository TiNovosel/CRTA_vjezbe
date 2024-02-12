# CRTA_vjezbe
Potrebno je napraviti radnu mapu repozitorija te klonirati udaljeni repozitorij:
```sh
mkdir as_git_vjezbe
cd as_git_vjezbe
git clone git@github.com:TiNovosel/CRTA_vjezbe.git
git status
```

#### Lista grana na kojima se nalaze pojedine vježbe

Vježbe su zamišljene na način da se zadaci nalaze na različitim granama. Svaka grana ima svoje `UPUTE.md` markdown upute u kojima možete pročitati pojašnjenje zadatka na odabranoj grani.  


- `main` - Na main grani se trenutno nalazite.
- `01_vjezba` - Dodavanje datoteke, prvi commit i push
- `02_vjezba` - Branch for developing 'Feature X'.
- `03_vjezba` - Branch for fixing bug 'Y'.3
- `04_vjezba` - Branch
- `05_vjezba` - Branch
- `06_vjezba` - Branch

Vježbe se nalaze na granama <strong>0X_vjezba</strong>.
```sh
git branch -r
```

Na prvu vježbu prebacujemo se pomoću naredbe: 

```sh
git checkout 01_vjezba
```

    