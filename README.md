MoveMate

Opis:
MoveMate je mobilna aplikacija koja koristi podatke o kretanju uređaja za prepoznavanje načina prevoza. Aplikacija analizira senzorske podatke (akcelerometar i žiroskop) i na osnovu njih klasifikuje da li se korisnik kreće pešice, automobilom ili nekim drugim vidom prevoza. Podstiče ga da smanjuje količinu CO2 u atmosferi, tako što će birati bolje načine prevoza.
Repozitorij projekta je: https://github.com/Vladan11111/MoveMate

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





MoveMate
Description:
MoveMate is a mobile application that utilizes device movement data to recognize the mode of transportation. The app analyzes sensor data (accelerometer and gyroscope) and classifies whether the user is walking, driving a car, or using another form of transport. It encourages users to reduce CO2 emissions by choosing more environmentally friendly transportation options.

Features:

Automatic detection of transportation mode based on sensor data
Simple and intuitive user interface
Provides challenges for extra points and rewards users based on their chosen routes and modes of travel
Technologies Used:

React Native – Mobile app development
PHP
Canva
Installation and Running:
Clone the repository and install dependencies:
git clone https://github.com/Vladan11111/MoveMate.git
cd MoveMate
npm install
npm start
npx react-native run-android

How It Works:

When a user signs up, their account is linked to a point system. Based on the number of points collected, a ranking list is created, where the top-ranking users receive rewards. These rewards are defined by admins, such as transportation providers and other organizations that can register in the app.
The app offers daily challenges that provide additional points.
The device tracks the user's movement and, using its sensors, determines how they are traveling. Routes are scored accordingly—walking earns the most points, while traveling by car earns the least.
Team:

Dejan Stanojević
Vladan Vukota
Damjan Drobac
Iva Dragojević
Future Plans:

Integrating an AI model for motion recognition
Expanding the solution to other platforms
Contact:
For any questions or collaboration inquiries, feel free to contact us via GitHub or email.
GitHub
Email: woit.pg@gmail.com

