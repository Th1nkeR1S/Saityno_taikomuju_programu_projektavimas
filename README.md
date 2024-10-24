# Saityno_taikomuju_programu_projektavimas

# Projekto pavadinimas
Krepšinio komandų rungtynių forumas

# Sistemos paskirtis
Sistemos tikslas – sukurti forumą, skirtą krepšinio fanams susirinkti ir aptarti savo įspūdžius ir pastabas apie krepšinio rungtynes. 
Tai vieta, kur vartotojai gali kurti temas, bendrauti tarpusavyje, komentuoti ir įvertinti kitų pasisakymus. 
Sistema taip pat skatina komunikacija tarp bendraminčių ir padeda atrasti žmonių su kuriais galėtų aptarti krepšinį.

# Funkciniai reikalavimai
- Administratorius rolė
- Svečio rolė
- Naudotojo rolė
- Galimybė kurti (registruoti) ir valdyti naudotojų profilius.
- Naudotojų reitingavimo sistema, pagrįsta dalyvavimu diskusijose.
- Galimybė naudotojams kurti naujas diskusijas ar prisijungti prie esamų.
- Diskusijų skirstymas pagal krepšinio sritis/temas (pvz., krepšinio rungtynės, komandos, žaidėjai).
- Įrašų ir komentarų įvertinimo sistema (balsavimas už arba prieš).
- Administratorių ir moderatorių galimybė valdyti diskusijų eigą, stebėti taisyklių laikymąsi, šalinti nekorektišką turinį.
- Paieškos sistema, leidžianti rasti diskusijas pagal raktažodžius, temas ar autorius.
  
# Pasirinktų technologijų aprašymas
- Back-end: .NET (C#)
- Front-end: React
- Duomenų bazė: MariaDB

 # Pagrindiniai taikomiosios srities objektai
 Krepšinio sritis/tema (pvz., krepšinio rungtynės, komandos, žaidėjai)-> Įrašas (gali priklausyti kelioms temoms) -> Komentaras
