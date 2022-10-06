| Küsimus | Linux | Windows | Linuxis kasutatud käsklus | Windowsis kasutatud tööriist |
|---|---|---|---|---|
| 1. Mitu protsessi kokku arvutis käib | 224 | 288 | ps -aux | wc -l | Task Manager -> Jõudlus -> Protsessid |
| 2. Milline on kõige esimesena käivitatud protsess? | ? | system.exe | ? | Process Explorer -> Start Time |
| 3. Milliste kasutajate protsesse arvutis käib? | USER, root, systemd-oom, systemd-resolve, systemd-timesync, avahi, messagebusy, syslog, kernoops, colord, rauno | ps -eo user | ? | Tegumihaldur -> Üksikasjad -> Kasutajanimi |
| 4. Kui kaua on arvuti järjest töötanud (up time) ? (Alternatiivselt võib vastata ka millal (kuupäev ja kellaaeg) arvuti viimati käima pandi?)? | 22m | 14h 03m | uptime | Task Manager -> Jõudlus |
| 5. Milline protsess käivitati kõige hiljem (viimasena)? | /usr/bin/gnome-shell | opera.exe | ps -aux --sort -pcpu | Process Explorer -> Start Time |
| 6. Milline on kõige rohkem protsessoriaega võttev protsess? | /usr/bin/gnome-shell | svchost.exe | ps -aux --sort -vsz | Process Explorer -> CPU Time |
| 7. Milline on kõige rohkem virtuaalmälu (aadressiruumi, commit, Virtual Size) võttev protsess? | /usr/bin/gnome-shell | ? | ps -aux --sort -pcpu | ? |
| Milline on kõige rohkem füüsilist mälu (working set) võttev protsess? |  | opera.exe |  | Process Explorer -> Working Set |
| Kui palju füüsilisest mälust (Physical Memory) on vaba? |  | 890 MB |  | Resource Monitor -> Memory -> Physical Memory |
| Kui palju on põhikettal (C:, /) vaba ruumi mahult (GB) ja protsentuaalselt? |  | 282.74 GB, 59% |  | Kettahaldur |
| Milline on kõige suurem kõvakettal olev fail ja kõige suurem kaust? |  |  |  |  |
| Võrrelge terminali käskude: sha1sum /dev/zero or sha1sum /dev/zero ja sha1sum /dev/urandom or sha1sum /dev/urandom protsessori nõudlust. Avage teine terminaliaken ja top samaaegseks käivitamiseks. Uurige millisele CPU alamtegevusele us, sy, id, wa, st jne kulub enim protsessori aega ja mitu protsenti kulub kummagi käsu korral? (Ainult Linuxis) Lisa ka ekraanipilt aruande juurde näiteks pärast tabelit. |  |  |  |  |
| Milline protsess kõige rohkem salvestusseadmele kirjutab, kõige rohkem salvestusseadmelt loeb? Millisesse faili antud protsess kõige rohkem kirjutab, millisest failist kõige rohkem loeb? (Ainult Windowsis) |  |  |  |  |
| Millise protsessi poolt tekitatud võrguliiklus on suurima mahuga? Vali antud protsessi poolt kasutatavatest ühendustest üks ning kirjuta välja järgnev: kohalik IP-aadress, kohalik port, ühenduse teise poole IP-aadress, port, latents ja antud ühenduse poolt kasutatav võrguliikluse kogumaht. (Ainult Windowsis) Lisa ka ekraanipilt aruande juurde näiteks pärast tabelit. |  |  |  |  |
| Sõber kurdab, et tema arvuti on oluliselt aeglasem kui varasemalt. Millise programmiga ja millise parameetrite abil saate tuvastada milline protsess või teenus muudab arvuti aeglaseks? |  |  |  |  |
