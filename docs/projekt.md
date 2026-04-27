# Projekti dokumentatsioon

## Stsenaarium
- **Kasutajate arv:** 14
- **Ettevõtte tüüp:** Veebiarendus ettevõte
- **Eritingimus:** Kiire kasv (skaaleerimine)

## Infrastruktuuri plaan
- Ubuntu 22.04 - tasuta, stabiilne ja laialdaselt kasutusel
- Docker konteinerid teenuste jaoks - lihtne skaleerida ja hallata
- Nginx veebiserver - kiire ja kerge

## Teenused
- Nginx - veebiserver, suunab päringud õigetesse konteineritesse
- Docker - iga teenus töötab omas konteineris, skaleerimiseks piisab ühest käsust
- PostgreSQL - usaldusväärne tasuta andmebaas veebirakendustele
- Gitea - isehostitav Git server, meie oma GitHub

## Konfiguratsioonifailid
- `configs/docker-compose.yml` - kõik teenused ja nende seadistused
- `configs/nginx.conf` - pordid ja marsruutimine
