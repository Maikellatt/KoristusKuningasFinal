# KoristusKuningasFinal

Koristus Kuningas on puhastusteenuseid pakkuv ettevõte, mille senine koduleht oli staatiline ja pakkus klientidele vaid põhiteavet teenuste kohta. Teenuste tellimiseks tuli klientidel ettevõttega eraldi ühendust võtta e-posti või telefoni teel, mis muutis kogu protsessi aeganõudvaks ja ebaefektiivseks.

Selle projekti eesmärk on välja töötada uus koduleht, mis ühendab endas kaasaegse veebidisaini, mobiilisõbralikkuse ning praktilise broneerimissüsteemi. Uus süsteem võimaldab klientidel reaalajas valida sobiva teenuse (nt kodukoristus, suurpuhastus, tekstiilipesu), määrata sobiva kuupäeva ja kellaaja ning broneering kohe kinnitada.

Tehnilisest küljest on lahendus ehitatud Vue 3 raamistikul loodud kasutajaliidesele, mis suhtleb Laravel 11 backendi kaudu andmebaasiga. Kõik broneeringud ja kliendiandmed salvestatakse MySQL andmebaasi, mis tagab töökindla ja skaleeritava andmete halduse.

Frontend on hostitud Netlify platvormil, mis tagab kiire laadimise ja lihtsa CI/CD töövoo. Backend töötab eraldi serveris (nt Zone.ee või VPS), kust Laravel pakub REST API teenuseid. Selline arhitektuur võimaldab süsteemi paindlikult arendada, hallata ja laiendada ka tulevikus.

Projekti tulemusena valmib täielikult funktsionaalne koduleht, kus kliendid saavad:

tutvuda ettevõtte teenuste ja hindadega,

teha broneeringuid otse veebilehelt,

saada kinnituse e-posti teel.

Ettevõtte poolel saab administraator:

hallata broneeringuid läbi backendi liidese,

vaadata klientide ajalugu ja andmeid,

muuta teenuste valikut ja hindu vastavalt vajadusele.

Lõpptulemus on reaalne äriline tööriist, mis tõstab ettevõtte efektiivsust ja muudab kliendisuhtluse mugavamaks, vähendades samal ajal manuaalset töökoormust.