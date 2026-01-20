# SZUD_hijerarhija_radnika

Ovaj program implementira jednostavan sistem za upravljanje hijerarhijom zaposlenih u firmi korišćenjem programskog jezika C. Hijerarhija je modelovana kao stablo, gde svaki radnik može imati jednog nadređenog (menadžera) i više podređenih radnika.

Svaki radnik je predstavljen strukturom Radnik, koja sadrži ime radnika, pokazivač na menadžera, listu podređenih i pokazivač na sledećeg radnika na istom hijerarhijskom nivou. Program omogućava dodavanje novih radnika pod određenim menadžerom, rekurzivnu pretragu radnika po imenu, uklanjanje radnika iz hijerarhije, kao i ispis kompletne hijerarhijske strukture u preglednom formatu.

Hijerarhija se inicijalno formira sa direktorom, menadžerima i zaposlenima, nakon čega korisnik može dinamički dodavati ili uklanjati radnike tokom izvršavanja programa. Program koristi dinamičku alokaciju memorije i rekurziju za rad sa hijerarhijskom strukturom.