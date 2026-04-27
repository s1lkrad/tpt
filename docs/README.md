# IT infrastruktuuri dokumentatsioon

## Miks me need valikud tegime

Valisime Ubuntu 22.04 sest see on tasuta, stabiilne ja laialdaselt kasutusel
mistõttu on lihtne leida abi ja juhendeid. Kuna meie eritingimus on kiire kasv,
valisime Dockeri mis võimaldab uusi teenuseid kiiresti lisada ilma kogu süsteemi
uuesti seadistamata. Nginx valisime veebiserveriksq sest see on kerge ja kiire
ning sobib hästi paljude kasutajate teenindamiseks. PostgreSQL valisime andmebaasiks
sest see on usaldusväärne ja tasuta. Gitea valisime sest projekti nõue on kasutada
isehostitavaid rakendusi ja see asendab meile GitHubi meie oma serveris.

## Meeskond ja tööjaotus

**Armand Mesikäpp** - Otsustav isik. Vastutas GitHub repo loomise, dokumentatsiooni
kirjutamise ja projekti koordineerimise eest.

**Kert Leppanen** - Vastutas serverite seadistamise eest, sealhulgas Ubuntu
paigaldamine ja Docker keskkonna ülesseadmine.

**Albert Raude** - Vastutas teenuste seadistamise eest, sealhulgas Nginx,
PostgreSQL ja Gitea konteinerite konfigureerimine.
