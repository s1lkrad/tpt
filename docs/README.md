# IT infrastruktuuri dokumentatsioon

## Kuidas me infrastruktuuri üles paneme

Kõigepealt paigaldame Ubuntu 22.04 masinale Dockeri, mis võimaldab meil
kõiki teenuseid konteinerites jooksutada ilma et nad üksteist segaksid.

Seejärel paneme üles Nginx veebserveri, mis võtab vastu kõik päringud
internetist ja suunab need õigetesse teenustesse. Nii saavad kasutajad
ligi meie rakendustele.

Pärast seda käivitame PostgreSQL andmebaasi, kuhu salvestatakse kogu
ettevõtte andmed. Andmebaas töötab Nginxist eraldi konteineris.

Viimaks paneme üles Gitea, mis on meie isehostitav Git server. Sinna
laadivad arendajad oma koodi üles ja saavad meeskonnaga koostööd teha
ilma väliste teenuste kasutamiseta.

Kõik teenused on kirjeldatud `configs/docker-compose.yml` failis,
millega saab kogu infrastruktuuri ühe käsuga käivitada.
