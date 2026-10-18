---
name: latviska-izteiksme
description: Pārraksta AI radītu vai stīvu tekstu dabiskā, cilvēciskā latviešu valodā (un citās valodās), ievērojot latviešu gramatiku un stilu, bez garās domuzīmes un ar vidējo domuzīmi tikai reti. Lieto, kad lūdz humanizēt AI tekstu vai padarīt to dabiskāku, dzīvāku un latviskāku.
---

# Latviska izteiksme

Šis skill pārraksta tekstu tā, lai tas skanētu kā rakstījis cilvēks, nevis valodas modelis. Galvenā valoda ir latviešu valoda. Ja teksts ir citā valodā, piemēro vispārīgos principus (A un B daļa) un tos pašus pieturzīmju noteikumus.

## A. Neapspriežamie noteikumi

1. Nekad nelieto garo domuzīmi (—). Tas attiecas uz visu izvadi: teikumiem, virsrakstiem, sarakstiem un dialogiem. Ja oriģinālā tā ir, noņem to, nemainot jēgu (sk. tabulu zemāk).
2. Vidējo domuzīmi (–) drīkst lietot, bet reti: ne biežāk kā vienu reizi īsā tekstā un ne vairāk kā aptuveni vienu uz 300 vārdiem garā tekstā. Lieto to tikai tur, kur komats, kols vai punkts skanētu sliktāk (sk. B daļu). Ja oriģinālā vidējo domuzīmju ir daudz, atstāj tikai vietas, kur tās tiešām palīdz, pārējās aizstāj. Skaitļu diapazoni (2020.–2024.) un dati tabulās ir izņēmums un limitā neietilpst, bet skrejošā tekstā diapazonu labāk rakstīt vārdiem.
3. Nemaini faktus, skaitļus, vārdus, nosaukumus, datumus, citātus, saites un kodu. Nepievieno jaunus faktus, piemērus vai viedokļus, kuru autors nav devis.
4. Saglabā autora nolūku, toni un personu (es, mēs, tu, jūs). Ja autora dzimte redzama no darbības vārdu un divdabju formām (rakstīju, pārliecināts, pārliecināta), saglabā to.
5. Atbildē atdod tikai pārrakstīto tekstu. Īsu piezīmi par izmaiņām pievieno tikai tad, ja lietotājs to lūdz.
6. Ja lietotājs lūdz tikai gramatikas vai pareizrakstības labojumus, nemaini stilu un saturu.

## B. Domuzīmju aizstāšana

Savienojuma defise (-) paliek vārdos, kuros tā pieder pie rakstības (piemēram, e-pasts). Garo domuzīmi (—) vienmēr aizstāj. Vidējo domuzīmi (–) pēc noklusējuma aizstāj ar tabulā norādīto variantu, un atstāj tikai retos gadījumos:
- izlaists izteicējs, kur latviešu pareizrakstība domuzīmi paredz un teikums skan dabiski ("Rīga – Latvijas galvaspilsēta"), ja šādu teikumu tekstā ir maz;
- viens spēcīgs pārtraukums vai pretstats, kur pauze runā skanētu skaidri un komats to nenovērstu;
- skaitļu diapazons īsā formā (2020.–2024.), arī datu tabulās.

Pārējos gadījumos pārraksta:

| Oriģināls | Kā rakstīt |
|---|---|
| Rīga – Latvijas galvaspilsēta | Rīga ir Latvijas galvaspilsēta. |
| Viņš atnāca – un visi apklusa | Viņš atnāca, un visi apklusa. |
| Vajag trīs lietas – laiku, naudu, pacietību | Vajag trīs lietas: laiku, naudu un pacietību. |
| Projekts (kas sākās pērn – ar mazu komandu) bija veiksmīgs | Projekts, kas sākās pērn ar mazu komandu, bija veiksmīgs. Vai arī iekavās, ja tas tiešām ir blakus piebilde. |
| 2020.–2024. gads | no 2020. līdz 2024. gadam |
| 10–15 minūtes | no 10 līdz 15 minūtēm, vai apmēram 10 līdz 15 minūtes |
| Dialogs ar domuzīmi replikas sākumā | Raksti replikas pēdiņās („Tā nevar,” viņa teica.) vai pārstāsti netiešajā runā |
| Virsraksts: Tēma – apakštēma | Virsraksts: Tēma. Apakštēma. Vai: Tēma: apakštēma |

Izvēlies tuvāko dabisko variantu: komats vai punkts, ja doma dalās; kols, ja seko skaidrojums vai uzskaitījums; darbības vārds "ir", ja domuzīme aizstāja izlaisto izteicēju; iekavas retām blakus piebildēm.

## C. Kā strādāt

1. Nosaki valodu, žanru (e-pasts, raksts, sociālie tīkli, akadēmisks darbs, stāsts), auditoriju un reģistru (sarunvaloda, neitrāls, oficiāls). Pārraksti tajā pašā reģistrā, ja lietotājs nelūdz citu.
2. Atrodi AI pazīmes (sk. D daļu) un stīvumu gramatikā (sk. E daļu).
3. Pārraksti. Mazāk labo, ja teksts jau skan dabiski. Pārlieku pārrakstīts teksts arī izskatās mākslīgs.
4. Pārbaudi pēc saraksta H daļā. Ja ir pieejams Bash, meklē izvadē garo domuzīmi (—), kuras nedrīkst būt nevienas, un saskaiti vidējās domuzīmes (–), lai tās nepārsniegtu A daļā noteikto limitu.

Labošanas dziļumu izvēlas pēc lūguma: viegli (tikai AI frāzes un domuzīmes), vidēji (noklusējums: frāzes, ritms, kalki, vārdu secība), dziļi (pārstrukturē rindkopas un argumentu plūsmu, bet saglabā saturu).

## D. AI teksta pazīmes un ko ar tām darīt

Vispārīgi (jebkurai valodai):
- Ievada frāzes, kas neko nesaka: "mūsdienu strauji mainīgajā pasaulē", "šajā rakstā mēs aplūkosim", "ir svarīgi atzīmēt, ka", "nav noslēpums, ka". Sāc ar pašu domu.
- Noslēguma kopsavilkumi un morāles: "kopumā", "noslēgumā var secināt", "galu galā". Beidz ar pēdējo konkrēto domu vai ar vienu skaidru nākamo soli.
- Pārāk gludi trīsdaļīgi uzskaitījumi (A, B un C) un pretstati "ne tikai X, bet arī Y". Lieto reti, dažādo uzskaitījumu garumu.
- Visi teikumi ar līdzīgu garumu un uzbūvi. Mainā īsus un garākus teikumus, bet bez mākslīga "ritma".
- Augsti, bet tukši vārdi: radīt pievienoto vērtību, sinerģija, holistisks, risinājumi, potenciāls, ceļojums (pārnestā nozīmē), atklāt, iedziļināties, nozīmīga loma, kļūst arvien aktuālāks. Aizvieto ar konkrētu apgalvojumu: kas, kam, cik, kad.
- Neskaidri apgalvojumi un hedžēšana ("varētu teikt, ka zināmā mērā"). Saki tieši vai neizsakies.
- Lieka formatēšana: treknraksts un aizzīmes tur, kur pietiek ar rindkopu. Sarunas vai stāsta tekstā lieto rindkopas.
- Uzmākīgs draudzīgums un glaimi ("lielisks jautājums!", "protams!"). Noņem.
- Retoriski jautājumi, uz kuriem pats uzreiz atbild.
- Emocijzīmes, ja autors tās nelieto.

Latviešu valodā papildus:
- Burtiski tulkotas angļu valodas konstrukcijas (sk. E daļu).
- Pārāk daudz vārda "tiek" un divdabju konstrukciju.
- Garas ģenitīvu virknes un lietvārdi tur, kur varētu būt darbības vārds.
- Aukstais, aprakstošais tonis tur, kur latviešu valodā dabiski skanētu sarunas intonācija.

## E. Latviešu gramatika un stils (izpētes rezultāti)

### 1. Vārdu secība
- Latviešu valodai ir relatīvi brīva vārdu secība, bet neitrālā pamatsecība ir teikuma priekšmets, izteicējs, papildinātājs (SVO). Tā ir visbiežākā gan rakstos, gan runā. Citas secības (papildinātājs priekšā, izteicējs pirmais) ir pragmatiski iekrāsotas: tās izceļ vai pretstata.
- Jaunā, svarīgākā informācija parasti nonāk teikuma beigās, jo uzsvars latviešu valodā visbiežāk krīt uz intonācijas frāzes pēdējo vārdu. Zināmo (tēmu) liek sākumā. Pārbaudi, vai teikuma pēdējais vārds ir tas, ko lasītājs lai paturētu prātā.
- Neatdarini angļu valodas fiksēto secību "apstāklis, teikuma priekšmets, izteicējs, papildinātājs" katrā teikumā. Mainot secību, saglabā jēgu: "Projektu īstenosim mēs" izceļ "mēs", "Mēs projektu īstenosim" izceļ darbību.
- Izteicēja novietošana pašā sākumā (VSO, VOS) ir ļoti reta un sarunvalodas vai dzejas iekrāsota. Nelieto to kā "izmainītu AI stilu".
- Apzīmētājs parasti stāv pirms apzīmējamā vārda ("jauns projekts", "Rīgas vecpilsēta"). Apzīmētāja pārcelšana aiz vārda ("asinis zelta") rada dzejisku vai emocionālu nokrāsu. Neizmanto bez iemesla.

### 2. Darbības vārds pret lietvārdu
- Latviešu valodā dabiskāk skan darbības vārds nekā nominalizācija. Aizvieto: veikt analīzi, analizēt; sniegt atbalstu, atbalstīt; veikt izvēli, izvēlēties; rast risinājumu, atrisināt; īstenot uzlabošanu, uzlabot; nonākt pie secinājuma, secināt.
- Izvairies no lietvārdu un ģenitīvu virknēm ("uzņēmuma attīstības stratēģijas ieviešanas process"). Sadali divos teikumos vai pārtaisi ar darbības vārdu: "Uzņēmums ievieš jaunu attīstības stratēģiju."

### 3. Darāmā un ciešamā kārta
- Latviešu valoda dod priekšroku darāmajai kārtai un nenoteikti personiskiem teikumiem. Teikums "Tika veikta analīze un tika sniegti ieteikumi" skan birokrātiski. Labāk: "Analizējām datus un ieteicām, kā uzlabot procesu." Vai nenoteikti personiski: "Mājā ceļ jaunu jumtu."
- Ciešamo kārtu ("tiek", "tika" + divdabis) atstāj tur, kur izpildītājs nav svarīgs vai nav zināms, un lieto reti, nevis katrā teikumā.
- Divdabju teicienus un garas darbības vārdu virknes ("sākot ar ... un beidzot ar ...") nomaini ar īsākiem teikumiem.

### 4. Locījumi, dzimte un skaitlis
- Latviešu valodā nav artikulu. Netulko angļu "the" ar "šis", "tas", un "a/an" ar "viens". Lieto tikai tad, ja tiešām norādi uz kaut ko konkrētu.
- Lietvārds ar noliegumu "nav" prasa ģenitīvu: "Nav problēmas", "Nebija laika". Divkāršs noliegums ir norma: "Nekas nenotika", "Neviens neatnāca".
- Piederību izsaka ar datīvu: "Man ir grāmata", "Viņai ir ideja". Nelieto "Es esmu ar".
- Atgriezeniskais vietniekvārds "savs" jālieto, ja piederība attiecas uz teikuma priekšmetu: "Anna paņēma savu somu" (nevis "viņas somu", ja tā ir viņas pašas soma). Tas ir viens no biežākajiem kalkiem no angļu valodas.
- Atgriezeniskie darbības vārdi (-ties) jāsaglabā: apņemties, pieteikties, rūpēties, pārliecināties.
- Pareizi saskaņo dzimti un skaitli starp lietvārdu, īpašības vārdu un divdabi (jauna lietotne, jauns dators, nesen pievienotie dati).
- Īpašības vārdu galotnes: noteiktā galotne pēc norādāmajiem vietniekvārdiem un nosaukumos ("šis jaunais projekts", "Vecā pilsēta"), nenoteiktā izteicējā ("projekts ir jauns").
- Nosaukumus oriģinālrakstībā (Google, Notion) labāk nelocīt, bet pārfrāzēt ar vispārīgu vārdu: "Google meklētājā", "Notion lietotnē".
- Skaitļa vārds: ar skaitļiem 2 līdz 9 un 20, 30 utt. lietvārds vienskaitlī vai daudzskaitlī pēc normas (divi galdi, desmit galdu, 21 galds). Pārbaudi galotnes.
- Parādi cieņu ar konsekventu "tu" vai "jūs" visā tekstā. Vēstulēs vienai personai "Jūs" var rakstīt ar lielo burtu, citur ar mazo.

### 5. Modalitāte un sarunas intonācija
- Latviešu valodā ļoti dabiska ir debitīva konstrukcija: "jāsatiekas", "jāpaspēj", "jāzina". Aizvieto stīvo "ir nepieciešams veikt" ar "jāveic", vai vēl vienkāršāk, ar "vajag", "der", "var".
- Daļiņas un saikļi dod sarunas krāsu: taču, tomēr, nu, jau, gan, vien, pat, tad. Nelieto tos mehāniski, bet ļauj tekstam elpot. Teikuma sākumā nav jābūt "Turklāt", "Tāpat", "Šajā kontekstā" katrā rindkopā.
- Frazeoloģija un teicieni (nākt prātā, ņemt galvā, nav ko darīt) dara tekstu dzīvāku, bet lieto tikai tad, ja tie atbilst autora reģistram.
- Deminutīvi (-iņš, -ītis, -īte) ir siltuma zīme neformālā tekstā. Oficiālā tekstā tos nelieto.

### 6. Biežākie kalki un aizstājēji
| Kalks vai AI frāze | Labāk |
|---|---|
| spēlēt lomu | būt svarīgam, ietekmēt |
| no manas puses | es, manuprāt |
| dienas beigās | galu galā, galvenais ir |
| ņemt par pašsaprotamu | uzskatīt par pašsaprotamu |
| sniegt ieskatu | parādīt, pastāstīt |
| pievienot vērtību | palīdzēt, dot labumu (un pasaki, kādu) |
| tas strādā (par programmu vai ierīci) | tas darbojas |
| tas ir par to, ka | runa ir par to, ka, vai uzreiz pasaki lietu |
| viens no | dažkārt vienkārši "viens", vai pārfrāzē |
| daudz dažādu | daudzveidīgs, vai nosauc konkrētus piemērus |
| būt iesaistītam | piedalīties, darboties |
| risināt problēmu | atrisināt problēmu, tikt galā ar problēmu |
| veikt darbību | izdarīt, paveikt |

Angļu valodas aizguvumus (deadline, feedback, meeting, team, mindset, insight, workflow) maini uz latviešu ekvivalentu (termiņš, atsauksmes, sanāksme, komanda, domāšanas veids, atziņa, darbplūsma), ja auditorija nav tehniska un ja latviešu vārds skan dabiski. Tehniskā tekstā (prompt, API, commit) atstāj iesakņojušos terminus.

### 7. Pareizrakstība un tipogrāfija
- Pēdiņas latviski: „šādas“. Iekšējām pēdiņām izmanto ‚šādas‘.
- Datums: 2026. gada 17. oktobrī, 17. oktobris. Mēneši un nedēļas dienas ar mazo burtu.
- Procenti ar atstarpi: 15 %. Decimāldaļa ar komatu: 3,5. Tūkstošu atdalīšana ar atstarpi: 12 000.
- Laiks: plkst. 17.30. Valūta: 15 eiro.
- Virsrakstos ar lielo burtu raksta tikai pirmo vārdu un īpašvārdus (nevis Title Case kā angļu valodā).
- Saīsinājumi ar punktu: piem., t. i., u. c., u. tml.
- Pārbaudi garumzīmes un mīkstinājuma zīmes (ā, ē, ī, ū, č, š, ž, ģ, ķ, ļ, ņ).

## F. Stila paraugs: ko mācāmies no latviešu klasikas

Izlasītais fragments ir Rūdolfa Blaumaņa humoristiskā "Īsa pamācība mīlēšanā" (sadaļa par satikšanos). No tā ņem šīs mācības:
- Konkrēti, sadzīviski tēli (klētiņa, govju kūts, grābeklis), nevis abstrakti vārdi.
- Sausa ironija un tieša uzrunāšana ar instrukcijas toni, ko izsaka debitīvs ("jāsatiekas", "jāsargājas").
- Īsi galvenie teikumi, kuriem seko papildinošas piebildes ar komatiem un iekavām, nevis garas lietvārdu ķēdes.
- Runas pagriezieni un nepiespiestas piebildes ("Drīzāk tad jau ..."), kas rada dzīvu balsi.
- Saprotams, viegls ritms bez liekām saitēm starp teikumiem.

Šis ir paraugs balsij, nevis veidne. Nekopē un neatdarini ne frāzes, ne arhaisku vārdu krājumu, ja tas neatbilst autoram.

## G. Piemēri

AI stils:
"Mūsdienu strauji mainīgajā digitālajā pasaulē ir svarīgi atzīmēt, ka kopienām ir izšķiroša nozīme uzņēmējdarbības attīstībā. Šajā rakstā mēs aplūkosim, kā kopienas var veicināt inovācijas, veidot sadarbību un radīt pievienoto vērtību."
Cilvēciskāk:
"Uzņēmējam reti iet viegli vienam. Kopiena palīdz atrast pirmos klientus, iedod padomu, kad plāns sagāzies, un dažreiz vienkārši atgādina, ka citiem ir tāpat. Paskatīsimies, kā tas darbojas praksē."

Ciešamā kārta un nominalizācija:
"Tika veikta datu analīze un tika sniegti ieteikumi procesu uzlabošanai."
Labāk:
"Analizējām datus un ieteicām, kā procesus uzlabot."

Kalks "savs":
"Anna paņēma viņas somu un devās uz staciju."
Labāk:
"Anna paņēma savu somu un devās uz staciju."

Domuzīmes:
"Mums vajag trīs lietas — laiku, naudu un pacietību."
Labāk:
"Mums vajag trīs lietas: laiku, naudu un pacietību."

Vidējā domuzīme, ko drīkst atstāt (reti):
"Rīga – Latvijas galvaspilsēta, bet sirds man pieder laukiem."
Šeit domuzīme aizstāj izlaisto "ir", un tā ir vienīgā tekstā. Ja šādu teikumu būtu vairāki, atstāj vienu, pārējos pārraksti ar "ir".

Noliegums:
"Tur nebija problēma."
Labāk:
"Tur nebija problēmas."

## H. Pārbaudes saraksts pirms atbildes

- Nav nevienas garās domuzīmes (—), arī virsrakstos un sarakstos.
- Vidējā domuzīme (–) ir lietota reti, tikai tur, kur tā palīdz, un nepārsniedz limitu no A daļas.
- Fakti, skaitļi, vārdi un citāti nav mainīti.
- Nav ievada un noslēguma frāžu, kas neko neziņo.
- Teikumi ir dažāda garuma, un katras rindkopas pēdējais vārds nes jauno domu.
- Darbības vārdi ir izmantoti tur, kur bija lietvārdu virknes. Ciešamā kārta nav katrā teikumā.
- Pārbaudīti "savs", noliegumi ar ģenitīvu, atgriezeniskie darbības vārdi, dzimte un skaitlis.
- Reģistrs (tu/jūs, sarunvaloda/oficiāls) ir konsekvents.
- Pēdiņas, datumi, procenti un skaitļi rakstīti pēc latviešu normām.
- Teksts skan skaļi lasot. Ja kāds teikums pa mēli neiet, pārraksti to.

## I. Avoti, uz kuriem balstīti gramatikas apgalvojumi

- Saulīte B., Auziņa I., Levāne-Petrova K. Teikuma priekšmeta, izteicēja un papildinātāja novietojums teikumā un teikuma intonācija latviešu valodā. Valoda: nozīme un forma 7, Latvijas Universitāte (vārdu pamatsecība SVO, mainītas secības nozīme, uzsvars intonācijas frāzes beigās).
- Latvijas Universitātes darbi par vārdu secību (Kalna, 2016; Zvīgule, 2019) un par latviešu valodas morfoloģiskajām īpatnībām (flektīva valoda, brīva, bet komunikatīvi motivēta vārdu secība).
- Rūdolfs Blaumanis, "Īsa pamācība mīlēšanā" (publiskā domēna darbs), stila novērojumiem.
