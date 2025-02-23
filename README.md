MoveMate

Opis:
MoveMate je mobilna aplikacija koja koristi podatke o kretanju uređaja za prepoznavanje načina prevoza. Aplikacija analizira senzorske podatke (akcelerometar i žiroskop) i na osnovu njih klasifikuje da li se korisnik kreće pešice, automobilom ili nekim drugim vidom prevoza. Podstiče ga da smanjuje količinu CO2 u atmosferi, tako što će birati bolje načine prevoza.

Funkcionalnosti:
Automatsko prepoznavanje tipa prevoza na osnovu podataka sa senzora, jednostavan i intuitivan korisnički interfejs. Daje korisnicima izazove za dodatne bodove i nagrađuje ih za izbor rute kojom putuju, kao i načina putovanja.

Tehnologije koje smo koristili:
- React Native – razvoj mobilne aplikacije
- PHP
- Canva

Instalacija i pokretanje:
Kloniranje repozitorijuma i instalacija zavisnosti:
git clone https://github.com/Vladan11111/MoveMate.git
cd MoveMate
npm install
npm start
npx react-native run-android

Kako funkcioniše:
- Korisnik kada se prijavi za njegov nalog se veže broj bodova. Na osnovu broja bodova se obrazuje rang lista, gdje najbolji na listi dobija nagradu. Te nagrade definišu admini, to jest prevoznici i slično koji se mogu prijaviti na aplikaciju. Aplikacija nudi dnevne izazove, koji donose dodatne bodove. Uređaj prati kretanje korisnika, i na osnovu senzora sa uređaja prepoznaje kako se kreće. Te rute se boduju, te najveći broj bodova se dobija ako ide pješke, a najmanje ako ide autom.

Tim:
- Dejan Stanojević 
- Vladan Vukota 
- Damjan Drobac 
- Iva Dragojević 

Planovi za budućnost:
- Ubacivanje modela vještačke inteligencije za prepoznavanje kretanja
- širenje rješenja na druge platforme



Kontakt:
Za sva pitanja i saradnju, kontaktirajte nas putem GitHub-a ili e-maila.
https://github.com/Vladan11111
woit.pg@gmail.com




