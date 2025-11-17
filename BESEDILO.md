# Uvod v Git
 HEAD
HalHribar1.sprememba
##HalHribar1.sprememba
>>>>>>> 59848a1803cb29d1b4f8c919a10c2cc9d182f214

Git je orodje, ki omogoča *sledenje spremembam* v datotekah in učinkovito *sodelovanje v skupinah*.  
Nastal je *leta 2005*, ko ga je Linus Torvalds razvil za upravljanje izvorne kode **Linux jedra**.  
Od takrat se je Git razširil in postal **standard** v svetu razvoja programske opreme.
<<<<<<< HEAD
Hal Hribar 2.sprememba

 HEAD

##Hal Hribar 2.sprememba
parent of 1d79d29 (2. realna sprememba 2.odstavek)
>>>>>>> 59848a1803cb29d1b4f8c919a10c2cc9d182f214

Git omogoča, da vsak razvijalec dela **lokalno** na svojem repozitoriju, nato pa spremembe deli z drugimi preko **oddaljenega repozitorija** (npr. GitHub, GitLab ali Bitbucket).  
S tem se zmanjša možnost konfliktov in izgube podatkov.

##Hal Hribar 3.sprememba 


## Glavne značilnosti

- **Zgodovina sprememb**: vsak commit predstavlja točko v zgodovini projekta.  
- **Veje**: omogočajo razvoj različnih funkcionalnosti vzporedno.  
- **Skladnost (merge)**: Git zna združiti spremembe različnih razvijalcev.  
- **Razpršenost**: vsak razvijalec ima popolno kopijo repozitorija.  
- **Zanesljivost**: Git zagotavlja integriteto podatkov s preverjanjem hash vrednosti (SHA-1).
-**Sprememba**: To je pa moja sprememba. 

## Pogosti ukazi

| Ukaz | Namen |
|------|--------|
| `git init` | Ustvari nov lokalni repozitorij |
| `git clone <url>` | Klonira obstoječi repozitorij |
| `git status` | Prikaže stanje sprememb |
| `git add <datoteka>` | Doda datoteko v pripravo za commit |
| `git commit -m "Opis spremembe"` | Zabeleži spremembe |
| `git push` | Pošlje spremembe v oddaljeni repozitorij |
| `git pull` | Povleče nove spremembe z oddaljenega repozitorija |
| `git branch` | Prikaže ali ustvari nove veje |
| `git merge <veja>` | Združi določeno vejo z trenutno |
| `git log` | Prikaže zgodovino commitov |



