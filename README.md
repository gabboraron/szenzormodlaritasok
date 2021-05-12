# szenzormodalitások

- [What is a smart city](https://www.youtube.com/watch?v=Br5aJa6MkBc)


**Tárgyköveelmény:**
- 2 zh - vagy vizsga
- önálló féléves feladat


## okos vs intelligens
- az intelligens képes tanulni, vagy legalábbis valamilyen ú tulajdonságokat szerezni
- az okos "csak" vezérlés, automatizálás, digitalizálás

## szenzor fogalma
> - Érzékelő ami valamilyen fizikai/kémiai mennyiséget, vagy annak változását mér
> - digitális mérés
> - digitális adatot tovább tudja küldeni vezetékes, vagy vezeték nélküli csatornán
> 
> **hátrány:** táplálás, adattovábítás módja, rendszer sebezhetősége, felhasználó életének megnehezítése, stb
> 
> ### szenzorok csoportosísása mérendő mennyiség alapján
> **szenzor:** Érzékelő ami valamilyen fizikai/kémiai mennyiséget, vagy annak változását méri. Digitális adatot ad ki magából. A digitális adatot tovább tudja küldeni vezetékes, vagy vezeték nélküli csatornán.   
> - mechanikai érzékelők
> - termikus mennyiségek
> - elektromos és mágneses mennyiségek
> - élettani paraméterek

![dikw pyramid](https://www.ontotext.com/wp-content/uploads/2018/03/DIKW-Pyramid.png)

## DAQ
> Kommunikációs infrastruktúra köti össze a kliens és központi rendszert:
> - Központi adat tároló és adat menedzselő rendszerek 
> - Üzemeltető és kiszolgáló személyzet infrastruktúrája 
> - rendszer irányító renddszerek

## DCS
> olyan rendszer ami központi vezérléssel távolról szabályozó körök működését és paramétereit lehet változtatni
> - kritikus infrastruktúráknál használt
> - helyi vezértlőt alkalmaz
> - a koomunikáció is lokális, amit esetleg távolról lehet monitorozni

## SCADA
> Legyen egy olyan rendszer ahol én távolról tudok beavatkozni, szabályozni, és monitorozni egyszerre, központosított vezérléssel távoli adatgyűjtéssel, erőművek, csővezetékeknél jó.
> 
> bonyolult rendszerekt képes felügyelni, a 
> 
> ![SCADA system](https://www.ssla.co.uk/wp-content/uploads/2018/10/scada.png)
> 
> **SCADA generációk:**
> 1. monolitikus, szigetszerű: egymástól függetlenek, zártak, külső kapcsolat nélkül, ideálsi erőművekhez
> 2. elosztott rendszerek, földrajzilag nagyobb kiterjedésű, LAN hálózatok, egymással is kommunikálnak
> 3. LAN nál nagyobb kiterjedéssel ugyanaz
> 4. IoT nagyon sok szenzorral
> 5. felhővel összekapcsolt rendszer
> 
> *felhasználható pl* 
> - távoli telemetria, beteg megfigyelés
> - veszélyesen/nehezen kezelhető helyek karbantártása
> - biztonsági rendszerek

**biológia jellemzők mérésére:**
- ekg  → ElectroCardioGraphy 
- eeg  → ElektroEncephaloGraphy 
- emg  → ElectroMyoGraphy 
- ecog → ElektroCOrticoGraphy
- testhő
- gsr
- súly
- mozgás

## nagymennyiségű adatgyűjtés kihívásai
- hálózat korlátai
- hardver korlátai
- feldolgozási kapacitás korlátai

## mérési elvek
**auszkultációs módszer**
- korotkov hangok detektálásán
- hátrány: egyetlen pillanatnyi érték, mandzsetta, leeresztési sebesség, orvos hallása mind befolyásol

**oszcillometriás módszer**
- automata vérnyomásmérők
- artéria pulzálása megjelenika felkarra helyezett mandzsetta nyomában
- pulzálás maximális: artériás középnyomással
- hátrány: a szorzók pontatlanok öregedéskor az artériák rugalmatlanok.

**tolometria**
- speciálsi esetben használják, mert drága

**PPG aléapú**
- hajszálerek térfogatváltozását regisztrálja
- hátrány: bonyolult és nehezen követhető

**A vérnyomásmérés pontatlan:** + 8Hgmm ha keresztbe teszed a lábad, +5Hgmm ha ülve méred. A kettő ösze is adódhat.

**vércukorszint mérése:**
- inzulint a langerhans szigetek termelnek, de ha a hasnyálmirigy tönkre megy akkor ez megszűnik
- ha a sejtek nem tudnak a vérből cukrot felvenni akkor a cukor a vérben marad => megnő a vércukorszint egy idő után ellenállnak a sejtek az inzulinnak.
- kémiai reakcióknál a vegyi anyagok szavatossága korlátos
- leolvasás automatizáltsága
- CGM: folyamatos vércukorszintmonitorozás, mérés kombinálva inzulinpumpával, mesterséges hanyálmirigy 
  - medtronic
  - abbot 

1. cukorbetegség
- rendszeres inzulinozás kell
2. cukorbetegség
- lépcsőzetes kezelés
- elég a diéta is
3. típusú cukorbetegeség terhesség alatt

**gyógyszerszedés** a gógyszeripar mérete = hadiipar + női kozmetikumok

- **pacemekerek:** mérjük az adatokat a testben átküldjük egy lokális tárolóba ami felküldi a felhőbe
- **emberi légzés monitorozása**: 
   - külső légzés: állanó légcsere zajlik a tüdő és környezet között: gond lehet a fulladás
     - **kilégzési csúcs áramlás mérő:** Lényegében azt méri, hogy egy kilégzés alkalmával milyen gyorsan jut ki a levegő a tüdőből, PEF
     - **Spirométer:** tüdő levegőbefogadó képességének mérésére való eszköz 
     - **Légzési rátát monitorozó öv:** Nyúlásképes pánt, ami a mellkas térfogatváltozását érzékeli 
     - **Légzésfigyelő/őr babákhoz:** Babaágy aljára helyezhető mozgás érzékelő matrac
     - **Légzésszámláló:** Alvás/horkolás monitorozás mikrofonnal
   - belső légzés: sejtek és szövetek légzés: asztma, CO fulladás
     - **Pulzoximetria:** folyamatosan érzékeli az oxigén szint változását, fájdalommentes, gyakran megbízhatatlan a perifériás érellenállás miatt egyes betegségeknéál


koleszterin mérés:
- LDL
- HDL

## EKG
> non invazív szívvizsgáló eljárás mely a szív elektromos jelenségeit vizsgálja a szívizom összehúzódásakor keletkező elektromos feszültség mérésével
- szív elektromos jeleit vizsgálja 
- **az ekg műkédési elve:** a szívben lejátszódó elektromos folyamatok a test felszínén is jól érzékelhetőek 
- három pont egy szabályos háromszögeet ad ki, középpontban a szívvel, ennnek a három pontnak az egymáshoz viszonyítható feszültségéből megmondható az aktuális változások a szívben

EKG görbe: egy szabályos felvételen az öt csúcsot lehet megkülönböztetni:
- `P` -  ingerület a szinusz csomóban (a pitvaron áthaladó elektromos impulzust, a pitvar összehúzódását jelzi)
- `Q` -  az ingerület kezdete a kamrákban, ez az apró negatív csúcs gyakran nem is látható, ha nagyon megnövekszik, az infarktust jelezhet
- `R` -  a legnagyobb csúcs a kamrákon végigterjedő ingerületet mutatja 
- `S` -  ez a negatív csúcs a kamrán végigfutó ingerület végét jelzi

más elemk a diagrammon: 
-  `T` - a kamra repolarizációját mutatja 
-  `U` - a normális görbén nem vagy csak alig látható, kóros állapotokban, például káliumhiány esetén látványos
-  `PQ intervallum` - pitvar - kamrai átvezetést jelent

**normális szívverés:**
-  `P`-hullám
-  `QRS` komplexum
-  `T` hullám

![ekg jel](https://github.com/gabboraron/szenzormodularitasok/blob/main/2011_0001_524_A_belgyogyaszat_alapjai_1.png)![ekg jelmagyarázat](https://m.blog.hu/ba/babosi/image/ecg1.gif)

**használható:** szív és keringési rendszer, terápia, távoli páciensmonitorozás, ambuláns ekg monitorozás, edzés/sportmonitorozás
- cardioblue
- wiwie
- savvy

más: MAP, iWatch, bioharness, quardio

## pacemakerek
> mellkasban vagy hasban műtét során elhelyezett  kis eszközök, ami elektromos impulzusok segítségével képes a szív ingerképző és ingerületvezető feladatait átvenni, kontrollálni
> 
> Aritmia esetén a szív vagy túl lassan (bradikardia), vagy túl gyorsan (tachikardia), vagy szabálytalanul veri a testbe a vért. Pacemaker beültetésével ezek a tünetek eltűnhetnek, a betegek teljes, aktív életet élhetnek.
> 
> *In 2013, multiple firms announced devices that could be inserted via a leg catheter rather than invasive surgery. The devices are roughly the size and shape of a pill, much smaller than the size of a traditional pacemaker. Once implanted, the device's prongs contact the muscle and stabilize heartbeats.* ~ https://en.wikipedia.org/wiki/Artificial_cardiac_pacemaker#Intra-cardial
> 
> **mit csinál?** elektródák detektálják a szív elektromos aktivitását és adatokat gyűjtenek, hogy ha kimarad egy ütem akkor helyettesítsék
> 
> beültetés: 1 óra, kulcscsont alatti területet helyikeg érzéstelenítik

- bradikardia
- öegedés és szívbetegség
- QT

egységei:
- elem
- számítógéppel ellátott generátor
- vezeték + szenzor -> elektróda

## EMG (elektromyography)
- felszíni
- izomból intramuszkuláris

## EOG (elctrooculography)
> szem köré elhelyezett elektrodákkal figyelem, hogy merre néz a páciens

## ECoG/ECG (elektrocorticography
- invazív mérés
- koponyán át fúrt lyukon kereszül néhány mikron csúcsátmérőjű mikrolektroda az agyszövetben
- a kis feszültségű magas frekvenciájú komponensek tisztán elvezethetőek
- jobb a felbontás

## EEG (elektroencephalography)
- elektrofiziológiai mérőeszköz, mely az idegsejtek elektromos aktivitását tudja mérni valós időben. Az EEG-vel elvezethető jel az elektroenkefalogram, amely egy komplex, több komponensű periodikus görbeként írható le.
- g.tec
- emotiv epoc
- mindrove
  - otthoni eeg szenzor, agyi jelek mérése és feldolgozása
  - brain computer interface

jelek:
- alfa ritmus: szemmozgásra blokkolódik
- beta
- gamma

> ### ERP (event related potential
> - eseményfüggő alkalmazás
> - valamely inger hatására kiváltott egyszeri potenciálváltozása EEG jelen 

alkalmazás:
- autonomus projekt
- neurophone
- driveby wire - braindriver
- braintalk (P300-as használatával)

## Alvás
- Fokozódik a sejtosztódás
- Sejtelhalás üteme csökken
- gyerekeknél 9 óra
- felnőtteknél: 7-9 óra

alvás szakaszai:
- 0 - alfa - ébrenlét
- 1 - théta - ébrenlét nyugodt
- 2 - alvási orsók - könnyű alvás
- 3 - lassú, deltahullámok
- 4 - rem szakasz: álmodik - mély alvás

frekvenciák alapján: 
- Ébrenlét, aktív: 20 Hz (15 - 40 Hz) 
- Ébrenlét, nyugodt: 10 Hz (9 - 14 Hz) 
– Könnyű alvás: 3,5 - 7 Hz 
- Mély alvás: 3,5 Hz alatt

**REM és nem-REM szakaszok:**
- elalvás után 70 percel
- aktív EEG
- bénult izmok
- gyors szívverés, légzés
- gyors anyagcsere
- paradox alvás

**fázisok sorrendje kötöttt:**
-  Non-RapidEye-Movement (NREM)
-  Rapid-Eye-Movement (REM) 

## Apnoe
- alvásfüggő légzészavar
- légzéskimaradás 

## Alvásmonitorozás:
- összetett komplex paraméter
- mozgásfigyelés
- szív és keringési paraméterek figyelése

> - aktivitás mérők
> - ágykeretbe helyezett monitorok
> - horkolás figyelők
> - stb

- teljesítőképesség, reakcióképesség mind csökken az alváshiánytól
- mikroalvás lehet a nagyon fáradt szint előtt

alvás észlelése:
- végtag mozgás
- szemmozgás
- fejmozgás
- pulzus változás
- légzés változás

kiegészítő szenzorok:
- vezető fejtartását nézni
- anti sleep pilot: folyamatosan számolja a vezető fáradtsági szintjét amit a megadott adatok alapján kiméri

Mercedes attention assist: kormány mozgást néz

Lexus: ccd kamerával oldják meg ami a kormányra van felszerelve 6 db leddel

Saab: a fej és szemmozgást néz, amivel figyelmi zónákat alakít ki, és ha a vezető tekintete nem figyeli az utat akkor jelez

Toyota: a szem nyitottságát nézi

## izzadás érzékelés
- különálló érzékelőkkel
- ruhába építve, intelligens textília,
- jellemzői:
  - életkor
  - nem 
  - lelki állapot, stressz szintje
  - mit evett előtt
  - fáradtsági szint
- biotex

## prezcíziós mezőgazdaság/állatenyésztés
multispektrális képek a mezőgazdaásgról megadja a kukorica stressz szintjét, szárasság stb szintjét
- [RTK](https://en.wikipedia.org/wiki/Real-time_kinematic) használata (https://www.youtube.com/watch?v=pOuYdxBWVyU)
- adatgyűjtés
- összefüggések és előrejelzések
- információ és tartalomszolgáltatás
- növelt hatékonyságú gazdálkodás
- növénytermesztési tudásközpont
- [agrodat projekt](http://agrodat.hu/) (mezőgazdaásgi tudásközpont döntéstámogató rendszer megvalósítása innovatív szenzorrendszerrel)
- talajszenzorok: nedvesség talaj vízszint, jégképződés, aktív fény intenzitása
- környezeti szenzorok, érzékeny csapadékmérő, szélsebesség, szélirány

### metadata kezelés
> - hőmérsékletet mérek a póznán a méréshez kell tudni a mérés idejét, hogy mikor jön be, mikor adja ki az oszlop az adatot, mikor mentette le az adatot, milyen időzónában van a mérőoszlop
> - smart vineyard
>
> **jelenlegi problémák**
> 
> - hatótávolság
> - energiafelhasználás
> - sok modalitás
> - mintavételezési idők problámja -> sok adat
> - adat aggregáció
> - védelem munkagépektől/emberektől, állatoktól/környezeti hatásoktól
> - vizualizációs problémák
> - adattárolás és adat visszakeresés, rövid és hosszútávú trendek, a környezet befolyása alapján előrejelzések késítése
> 
> mivel nagyon sok adat keletkezik, ezért érdemes átlagokat kezelni, hogy ne a nagy adatmennyiséget kelljen kezelni

## [fruition sciences](https://fruitionsciences.com/en/home):
- növényi nedv áramlás szenzorral megmondható mikor optimális a szüretelés
- analitika, javaslatok az öntözésről
- szőlészeti műveletek és mérések rögzítése

## szenzorok adattovábítási megoldásai
### vezeték mentes
![spektrumok](https://www.netfizika.hu/sites/default/files/pictures/Feladatok/Szamolos/Elektromagnesseg/Magneses/63/sp.jpg)

#### IEEE 802 csoportok
- IEEE 802.1 Magas szintű LAN protokollok
  - 802.1D – Spanning Tree Protocol
  - 802.1Q – Virtual Local Area Networks (VLAN)
  - 802.1aq - Shortest Path Bridging (SPB)
- IEEE 802.2 Logical link control és Media Access Control
- **IEEE 802.3 Ethernet**
- IEEE 802.4 Token busz (feloszlatva)
- IEEE 802.5 Token Ring (vezérjeles gyűrű)
- IEEE 802.6 Városi hálózatok (feloszlatva)
- IEEE 802.7 Koaxiális kábelt használó alapsávi LAN-ok(feloszlatva)
- IEEE 802.8 Fiber Optic TAG (feloszlatva)
- IEEE 802.9 Integrált LAN szolgáltatások(feloszlatva)
- IEEE 802.10 Együttműködő LAN-ok biztonsága(feloszlatva)
- **IEEE 802.11 Wireless LAN (Wi-Fi zárójelentés)**
- IEEE 802.12 igény prioritások
- IEEE 802.13 (nem használt)
- IEEE 802.14 kábel modemek (feloszlatva)
- IEEE 802.15 Wireless PAN
- IEEE 802.15.1 (Bluetooth zárójelentés)
- IEEE 802.16 Alapsávi vezetéknélkü hozzáférés (WiMAX zárójelentés)
- IEEE 802.16e (Mobil) alapsávi vezeték nélkül hozzáférés
- IEEE 802.17 rugalmas csomag gyűrű
- IEEE 802.18 Rádió szabályozási TAG
- IEEE 802.19 Coexistence TAG
- IEEE 802.20 Mobil alapsávi vezeték nélküli hozzáférés
- IEEE 802.21 Média független kezelés
- IEEE 802.22 Vezeték nélküli regionális hálózatok

a párhuzamos adatküldés nagyban megnövelte a sebességet

> **IEE 802.11**
> - Határok nélküli médiumot használ 
> - A külső jelek ellen védtelen 
> - A közeg jóval kevésbé megbízható mint a vezetett hullámú összeköttetés esetében 
> -  Dinamikus topológia 

![wifisec](https://pbs.twimg.com/media/DF6XjSeXkAAvbUo.jpg)

- csma/ca - az állomás jelentkezik, amire választ kap ahhoz hogy adhasson
- csma/cd - az eszköz érzékeli az ütközést és vár 

*wifi jelenlegi titkosítása 2018 óta WPA3, Simultaneous Authentication of Equals (SAE) kulcscsere protokol a berendezések között* 


#### bluetooth
![bluetoth history](https://miro.medium.com/max/4000/1*_GjhWQieYTUl_2mbTehkJQ.png)

*könnyen hackelhető*

**verziók:** 
- 3.0 -ban a pan hálózatot kinyitotátk egy hálózati hozzáférésre mert beleillesztették a wifi protokolt
- 4.0 -ban low energy protokollt adtak bele
- 4.2 - ben IoT támogatást és IPv6 támogatást és titkosítást kapott
- 5 -ben 4Xtávolság és 8Xsebességre növelte a low energy megoldásokat
- most az 5.3-nál járunk, 243 méteres távolságra szól
  - 1 master 7 eszközt szolgál ki, és több százat alvó állapotban

**basic rate és LE**
- BR: frekvenciamodulálásst használ, 1 tick 302.5 us
- LowEnergy: 1Mb/s

![brle](https://www.researchgate.net/profile/Karen-Scarfone/publication/329972964/figure/tbl2/AS:708926916030464@1546032756454/2-Key-Differences-Between-Bluetooth-BR-EDR-and-LE.png)

![howitworks](https://www.researchgate.net/profile/Ee-May-Fong/publication/259246800/figure/fig5/AS:297112509140993@1447848550198/Bluetooth-communication-between-the-transmitter-and-mobile-devices.png)

#### wibree
- Low-power wireless local area network 
- Hatótávolság 5 - 10 méter 
- Frekvencia: 2.4-GHz (RF) band. 

#### ant/ant+
- fitness eszközökhöz használt.
- https://www.thisisant.com/
- Egy 2032 gombelem: 25uA/év 
- skálázható
- **ANT** egy kommunikációs protokoll 
- **ANT+* egy menedzselt hálózat eszközök között
  -  Üzenet ráta 0.5Hz -> 200Hz (8byte adat)
  -  Max: 65.000 szimultán kapcsola 
  -  1.9V CR2032 elemmel tipikusan 5 év üzemid
- cél piacok: 
  -  Suunto 
  - Garmin 
  - Timex 
  - wahoo 
  - Sony Ericsson(Android) 
  - HTC 
  - Samsung 

![ant](https://www.researchgate.net/profile/Nadeem-Mehmood/publication/285510534/figure/fig1/AS:367752901611520@1464690532770/hArmor-System-Modular-Architecture_Q320.jpg)![ant+](https://lh3.googleusercontent.com/proxy/ZoCFi0-uQOMWuHYv3GADWOMEjuUR6smHNo7HJErJR8O0VyOyBACHgx4S3X7aAz_ucoJFRNtxqIEXsn-Kk0MnpwlX22zflmhCkzmtQs90Bu3xfChtIQnC_AYzHwnA)

#### zigbee
>  http://www.zigbee.org/
> - okosházakban használt technológia
> - Mindenhol használható frekvenciák 2.4 GHz
> - WPAN –Wireless Personal Area Networ 
> - falon/vizen nehezen megy át
- 100m - ig
- 250kbps
- ism sávon: nem kell hozzá külön frekvenciengedély hogy használjuk.

> **ZigBee hálózat:** két féle csomópont van:
> - Központi egység
>   - Folyamatos tápellátás, elegendő számítási kapacitás
>   - Hálózat beacon üzeneteinek küldése, a hálózat felállítása, az egyszerű csomópontok szervezése, a csomópontok paramétereinek tárolása, a párosított csomópontok üzeneteinek továbbítása
> - Egyszerű csomópont
>   -  csak a központi egységgel tudnak közvetlenül kommunikálni
>   -  Véges tápellátás 
>   -  Folyamatosan keresik az elérhető hálózatokat 
>   -  Adatküldés csak ha szükséges  
>
> Útvonalkeresés *broadcast* üzenettel. MAC szintű titkosítás.

##### Zigbee 3.0
> Megbízható, robosztus, kis energia fogyasztás,skálázható,biztonságos, globális (2.4GHz) , 130+ eszköz definíció /2016/
> 
> **Biztonsági rések**
> - Azonosítás kezdeményezés, 
> - factory reset
> - kommunikációs csatorna állítás
> - 100 m-ről lámpa kapcsolgatás

#### 802.11.ah
- 1 km
- 40 mbps

#### nfc
-10 cm
424 kbps

#### long range uhf
- még minidg ism
- Kb.: 10 km hatótávolság
- extrém esetben yagi antennákkal akár 160 km-is elérhető.
- frekvenciasáv: 433 MHz
- nagy hatótávolságú dronvezérléshez alklamas lehet
- Frekvencia ugrás, áthatol fákon és tárgyakon 
- Előszeretettel használják RC berendezésekben 

#### dash7 
- félkatonai felhasználása van
- alacsony a fogyasztása
- kb 1km a távolság
- civil: CO2 figyelés
- jól megy át vizen

#### UWB
- vezeték nélküli továbbítás
- szabványosítás és engedélyeztetés alatt áll
- 400-600Mbit/s és feljebb
- alacsony fogyasztású
- rövid ideig ad, viszont nagy órajelen
- felhasználás: egészségügy, helymeghatározás, behatolás védelem, ütközés elkerülés

![UWB spektrum](https://d6qq37vs6ar1f.cloudfront.net/wp-content/uploads/2017/05/eliko_joonis_05-02-900x525.jpg)

### Antennafajták
- chip antennák
- porcelán
- vezeték (meg van határozva, hogy hány centi lehet a kábel
- trace antennák: nyák megmarva, amihhez az isp32 chippen van az antenna

**külső antennák:**
- u.FL: kis konektor, ha kivezetnénk akkor hasznos
- RPSA: nagyobb

### LPWAN technológiák
Nagy távolságra küld adatokat, kis energiával. tipikusan csillag topogóliában aaz adótól vedő jelet egy fogadó az interneten adja tovább.
- LoRa/LoRaWAN
- SIGFOX
- NB-IoT
- LTE-M
- EC-GSM-IoT
- RPMA
- Weightless

### LoRa
> #### Chirp
> - up chirp: alacsony frekvenciáról amagasra megyek T idő alatt
> - down chirp: magasról megyek alacsonyra T idő alatt.
>
> - maga frekvencia adja az adatot, ezért nem fontos, a zajterhelés
> - fontos hogy kontinesenként változik az engedélyezett és használt frekvenciasáv!
>
> ![lra network](https://miro.medium.com/max/810/1*mJo0_GbLTqKr6R0oxV2DTg.png)
>
> kb 5-6 km a hatótávolság ait egy bázisállomás le tud fedni
> 
> lehetséges végberendezés: 1 tébla üzenete 1 bájt, 

- gyenge megbízhatóság, nincs grancia késleltetésre
- kis adatok gyorsan mennek át

### Sigfox
- 50 km körüli cellaméret, 
- 600bit/s - 100bit/s
- néhány ibtes rendszer

lefedettség: https://www.sigfox.com/en/coverage

![lora vs sigfox cover](https://www.libelium.com/wp-content/uploads/2018/10/lorawan_coverage_map3.png)

### NB IoT
Frekvenciákat vesz meg az operátor maiket bázisállomásokhoz rendel, és azon képes kommunikálni.

**Az 5G kompatibilis az NB IoT rendszerrel**

## vezetékes kommunikáció:
- homeplug - 100 m
- Ghm
- LonWorks - 1.5 km
- PCLPRIME - 100 km

soros kommunikációs:
- RS232 szabvány, DB-9 konnekor
- `/dev/ttyS*`
- `COMx`
- USB-re konvertálható, puferelt komunikációval, ami miatt széteshet a kapcsolat.

## USB
![usb history](https://resource01-proxy.ulifestyle.com.hk/res/v3/image/content/2280000/2280606/20190226-USB-32_1_1024.jpg)
![usb colors](https://www.storagereview.com/wp-content/uploads/2020/04/StorageReview-04-USB-Color-Convention.png) 
![usb covering](https://i.pinimg.com/originals/a8/a6/f4/a8a6f4a3b8846fffb0628c92dc7a4f5d.jpg)
![power](https://filestore.community.support.microsoft.com/api/images/d5c21b02-2386-4274-abba-1d4fdfd8e35c?upload=true)

**otg**: olyan megoldás ahol mindkét fél kliens és nem master slave alapú, mint egyébként az usb.

> ### USB hub:
> - akármennyi eszköz csatlkaozhat rá és egy másk hub is.
> - min 0.5 watt max 2,5 watt leadásra képes.
>
> ![hub piramis](https://www.keil.com/pack/doc/mw/USB/html/tiernetwork.png)
>
> - aktív hub:   saját táp kábellel
> - passzív hub: egyenlően osztja szét az áramot a kliensek között, 500mA
>
> Lassú bemeneti jelet is gyorsnak veheti ha a maellé betett eszköz gyorsabban ad jelet. EKkkor viszont a lassúból a jelet ismételni kezdi. Tipikus probléma billentyűzet-egér kapcsán.
 
### USB kapcsolat
- hosszabítót nem illik használni


### eszköz csoportok
- kompozit:
  -  több interfész, melyek egfymástól függetlenül vezérelhetőek
  - minden interfészhez külön driver
- compound szköz: egyetlen driver, több funkcionalitás, pl egér+billentyűzet

![packet típusok](https://www.usbmadesimple.co.uk/ums_g_setup.gif)

## textil alapú vezetékek *(textile wire, conductive textile)*
- Olyan textil, olyan fonal ami vezeti az áramot.
- teljes áramkörök, kapcsolók és ledek is ráköthetőek

![kábel](https://ars.els-cdn.com/content/image/3-s2.0-B9780081022283000116-f11-14-9780081022283.jpg) ![arduino](https://i.pinimg.com/originals/64/cd/85/64cd855ab25ae30c9146ec664eed1c3b.jpg)

- gyártása: valamilyen vezető anyagba tesznek fonalat, vagy fonalat áztatnak vezető anyagba.
- a hajlítások sajnos csak egy ideig képesek működni így.
- hátrányai:
  - szigetelési probléma, ezek szigeteletlen fonalok
  - nehéz javíthatóság és moshatóság
- felhasználás:  
  - hadiipar: vadászgépek takarása
  - tűzoltók/vegyvédelmisek PPE ruhái
  - szenzorokkal: hőmérséklet, páratartalom, ekg, stb
## I2C (inter IC)
> vezetékes összekapcsolás integrált áramkörök összekapcsolására
- busz alapú, két vezetékkel szinkron átviteli rendszer
- 2006-óta nem fizetős, de a cím bejegyzése az.
- sok modul támogatja, master és sok slave rendszerben.
  - a master adja az órajelet
  - master és slave szerep felcserélhető
  - felhúzó elllenállással


## Fogalmak
> - szenzor -  Érzékelő ami valamilyen fizikai/kémiai mennyiséget, vagy annak változását méri. 
> - IoT - internet of things, okosház, okosautó, precíziós gazdálkodás, stb
> - telemedicina - távmonitorozás vagy távdiagnosztizálása a betegnek
> - ICT - information and communication tech
> - távmonitorozás - pl koloszterin mérő, pacemaker, ekg, eeg, stb vagy talajnedvesség, időjárás, stb
> - WAN - Wide Area Network (10-100km) országos
> - MAN - Metropolitan Area Network (5-10km) városi
> - PAN - Personal Area Network (2-5m) bluetooth, automata beléptetés, stb
> - WPAN - 802.15 – Wireless Personal Area
> - szisztolé - a vérnyomás magasabb érétéke, túl magas értéke magyavérnyomásra utal, a szívizom öszehúzódásból ered
> - diasztolé - a vérnyomás alacsonyabb érétéke, magas értéke az erek rugalmatlanságát jelzik
> - variabilitás -  a szív miként képes a belső és külső környezet megváltozott terheléseire a szívveréstől szívverésig eltelt időtartamot folyamatosan megváltoztatni 
> - fehér
> - hipertónia - magas vérnyomás
> - auszkultáció -  Korotkov hangok detektálásán alapul; **Hátrány:** egyetlen pillanatnyi érték, mandzsetta befolyásol, leeresztési sebesség befolyásol, szubjektív a hallhatóság 
> - Korotkov -  Az először hallható erős koppanó hang (Korotkov 1-es hang) a szisztolés vérnyomás megjelenését mutatja, a hang teljes megszűnése (Korotkov 5-ös hang) a diasztolés vérnyomást jelzi
> - mandzsetta - vérnyomásmérő 
> - Oszcillometriás módszer - Automata vérnyomásmérők; Az artéria pulzálása megjelenik a felkarra helyezett mandzsetta nyomásában; A pulzálás maximális:artériás középnyomással (MAP) ebből származtatott A szisztolés és diasztolés érték; Hátrány: a szorzók pontatlanok, öregedés→artériák rugalmatlanok 
> - artériás -  főütőeren átmenő
> - Tonometria - Legpontosabb nem invazív mérési módszer – Mechanikai tapintófejjel rögzítésre kerül a csuklóartéria pulzálása (folytonos nyomásgörbe) – Hátrány: költséges megoldás
> - PPG-alapú -  A fotopletizmográf (PPG) a hajszálerek térfogat változását regisztrálja (pl:a bal kéz egyik ujjbegyén), plusz mandzsettával mérik + EKG görbe – Hátrány: bonyolult, sok nehezen követhető változó
> - glükóz - szőlőcukor 
> - Inzulin - Az inzulin serkenti a máj glikogénraktározását és a sejtek glükózfelvételét, ily módon csökkenti a vércukorszintet
> - Inzulinreceptor - érzékeli a az inzulint aminek hatására glükóz áramlik be a sejtekbe
> - Inzulinrezisztencia - a sejtek idővel ellenállnak az inzulin sejthártya nyitogató kísérleteinek
> - Diabetes 1 - Inzulin adás szükséges (rendszeres) – A hasnyálmirigy inzulint termelő béta-sejtjeinek pusztulása következtében nincs elegendő inzulintermelés 
> - Diabetes 2 - Lépcsőzetes kezelés – Életmódváltoztatás→ testsúlycsökkentés – tablettás antidiabetikus gyógyszerek 
> - Tesztcsík - Tesztcsík (többnyire külön az egyes mérési paraméterekre) – színelváltozások egyértelmű és minél pontosabb leolvasása
> - Lándzsa (vért veszünk szúrással)
> - Fonendoszkóp - sztetoszkóp, nyakbakasztós doktorbácsis hallgatózó
> - Elektrokardiográf - [EKG](https://github.com/gabboraron/szenzormodularitasok#ekg)
> - Einthoven-háromszöget - az ekg mérés alapja, nevét feltalálólájórl kapta
> - depolarizáció - elektromos kisülés a szívben
> - repolarizáció - elektromos újratöltődés a szívben
> - Kilégzési csúcsáramlás mérő  - Lényegében azt méri, hogy egy kilégzés alkalmával milyen gyorsan jut ki a levegő a tüdőből. A leolvasott érték az ún. kilégzési csúcsáramlás értéke (peak expiratory flow, PEF), egysége l/perc
> - Vérgázanalízis - artériás vér pH, CO2, stb értékei
> - Oxigénszaturáció - a hemoglobin oxigénnel való telítettségének mértéke százalékban. Pulzoximéterrel mérhető
> - SAO2 - oxygen saturation as measured by blood analysis
> - Spirométer - A tüdő levegőbefogadó képességének mérésére való eszköz 
> - Testzsírmérés - hány kg
> - AUV - autonomous underwater vehicle
> - ROV - Remotely operated underwater vehicle
> - Koleszterin - LD/HDL
> - LDL - low density lipoprotein
> - HDL - high density lipoprotein
> - VLDL - very-low-density lipoprotein.
> - laktát - a tejsav ionos (elektromosan töltött) formája, magas energitartalommmal
> - hemoglobin - vörösvértest
> - triglicerid -  a táplálkozás során felvett zsírok legfőbb alkotóelemei, illetve a szervezet zsírraktárai is főként ezekből épülnek fel
> - Antropometria - az emberi test leírható és mérhető jellegeinek rendszerezésével és egybevetésével foglalkozik
> - NRZ - USB-n használt non-return-to-zero kódolás
> - AES -  MAC szintű titkosítás, zigbeenél
> - ULP -  ultra alacsony fogyasztás → évekig működik 
> - UWB - alacsony fogyasztású Ultra szélessáv 
> - PCB - antenna, vezető útvonalakkal van felépítve a nyákon/ban
> - u.FL - egy kis konnektor, hasznos, ha ki szeretném vinni műszerházon kívülre az antennát
> - RPSMA - nagyobb antenna csatlakozó
> - vivőjel nélküli kommunikáció - 
> - pervasive 
> - mesh hálózat
> - SKKE - Biztonságos: Symmetric-Key Key Exchange
> - ISM - nem kell engedély hozzá
> - ad-hoc - központi vezérlés nélküli,  Wi-Fi hálózatok, amelyek általában ideiglenes jelleggel jönnek létre.
> - hullámhossz - az a távolság, amekkora távolságonként a hullám ismétlődik
> - pH - savasság, bázikusság mértékegység

## Arduino
- nyílt hardver
- c++, processing, java
- az alap alaaplapra shieldeket lehet tenni
  - TFT
  - audio
  - gsm
  - wifi
  - stb
- atmel mikrovezérlővel működik alapvetően, de azért más is előfordul: https://www.arduino.cc/
- egy lebutított programozói feületet ad amivel sok mindent lehet csinálni, és mivel egy hardverhez már könnyen lehet kész API így az könnyen használható, szemben a Texas STM32-es rendszerekkel
- legelterjedtebb az arduino uno, és arduino nano
- [*pin out*](https://www.google.com/search?sxsrf=ALeKk01WQs3_ikVUubfXsZXTRREZhV9e3g:1617797162800&source=univ&tbm=isch&q=arduino+pinout&sa=X&ved=2ahUKEwia59OJjOzvAhVQ6aQKHSTMAoAQjJkEegQIBhAB&biw=927&bih=970#imgrc=ZwVoFnEq8OqP0M) diagrammon van, hogy melyik lábra mi köthető. ![arduio pin out](https://images.prismic.io/circuito/8e3a980f0f964cc539b4cbbba2654bb660db6f52_arduino-uno-pinout-diagram.png?auto=compress,format) 
- `Tools\Board\` menüben ki kell választani melyik alaplapra fordítsa a bináris kódot

**A program részei:**
- globális változók megadása
- `setup(){}` függvény egyszer fut le
- `loop(){}` végtelenszer fut, ez maga a főprogram

**Analóg és digitális jelek:**
- 14 digitális ki/bemenet
  - `digitalWrite(láb, érték)` ahol `érték` az `0` vagy `1`
  - `digitalRead(láb)`
- 6 analóg láb bemenet, 0-123-ig 10 bites szám arról, hogy az adott pinen milyen áramerősséget mért: `analogRead(láb)`
  - analóg kimeneten `analogWrite(láb, érték)` formában 0-255 közötti számmal oldjuk meg.

szimulátor: https://www.tinkercad.com
költségtervező szimulátor: https://www.circuito.io/

lednél hoszú láb a pozitív

# Adatáramlás - DAQ
- végberendezés
  - adatgyűjtő 
  Vagy nagy fokon integrált rendszerek vagy nagy méreteket öltene, a hűtés, stb okán
  - nyers adatokat használ
  - adat töredékek kinyerhetőek
- köztes réted
  - Itt tároljuk a feldolgozott adatokat.


> Az állapotváltozásokból trenek alakíthatóak ki.
 
**Problémák:**
- sok adat, sok a redundáns adat is
- hibás és téves adatok
- nyílvánvaló adatok feldolgozása egyszerű, és a több szenzorjel közötti korreláció az érdekes
- az adat kereshető és nem túl redundáns tárolási módja
  statisztikák szerint: 
  - az adatok 78%-a felesleges
  - 22%-a dokumentált
  - 5%-a elemzett

A mintavételi frekvencia a maximális frekvenciától függ.

adatszűrés:
- zaj levétele
- jelek elkülönítése egymástól
- jel redundancia csökkentése
- adatforrás alapján:
  - szövegfájlból dolgozó
  - adatbázisbló dolgozó
  - bináris fájlból dolgozó
- hibareakció szerint:
  - hiba esetén leálló szűrő
  - automatikus javítást megkísérlő szűrő
  - hibás adatot eldobó/kihagyó
- optimizmus szerint:
  - pozitív szemléletű - adatok túlnyomórészt jók
  - negatív szemléletű - alapvetően azt mondják, hogy már hibás az érték, redundancia kell a rendszerbe, hogy csökkentsük a hibás méréseket
- jel karakterisztika szerint:
  - felületáteresztő: vágási pont *alatti*  értékektet kiszűri
  - aluláteresztő:  vágási pont *feletti* értékektet kiszűri
  - sáváteresztő: egy tartományon belüli értékeket neged át
  - lyukszűrő: egy sávban levő értétkeket *nem* enged át

> ## Adaptív szűrés folyamata:
> 
> - beérkező adatok összetettek
> - adaptáció = alkalmazkodás
> - szűrési paraméterek/tulajdonságok báltoztatásával a keletkező szűrtadat lényeges/fontos információkat nagyobb arányban tartlamazza
> 
> ## Előfeldolgozás:
> - simitás: ablakozunk, valamilyne ablak mérettel átlagokat hozunk, az adat mennyisége áltozatlan
> - aggregálás: sok adatból egy adatokt csinálunk, valhogy átlagolunk pl
> - küszöbözés: a lentésre fókuszálunk, nem az értékre, szinteket határozunk meg, amiket ha átlép az érték figyelembe vesszük
> - idősor analízis: a m.érés idejét és a mérést öszevetve használhatunk statisztikai eljárásokat, teát ha egy folytonos sorból kiveszünk valamilyen minta szerint adatokat akkor abból lehet valamilyen idő függvéányében jelezhető értéket megmondani
> 
> **független és összefüggő adatok:**
> - beteg közérzete mellé időjárás/hold ciklus/stb hozzárendelése
> 
> **döntéselmélet:**
> - adatok feldolgozása után döntési kényszerbe kerülhetünk, *pl: a páciens nem mozog x órája*
> - döntési szituációban , döntést ajánljon amely a legnagoybb várható hasznoságot biztosítja.
> - riaasztási események generálása egy döntési esemény alapján
> *pl: MTBF a hard diskeknél, mikor a hard disk részeinek elromálása közti időt adjuk meg*
> - **Dscriptive anlytics**: mi történt, és mia a vlasége, hogy újra leőfordul? *pl eltört a lábam, és mivel megoldható*
> - **diagnostic analytics**: miért történt az adott esemény? Mivel kiküszöbölhető? *pl: azért tört el a lábom, mert a csontritkulásom xy állapotban*
> - **predictive analytics**: mi fog történni? Mennyi ideje van a berendezésnelk az első elromlástól vagy az első elromlásig? *pl: egy központi adatgyűjtő szólna, napokkal előre, hogy lecsökkent a kalcium szint és igyunk pl tejet, hogy rndbejöjjünk.*
> 
> ![pragmatica](https://pragmaticarchitect.files.wordpress.com/2016/01/conversionrate_example_01.png)

# IoT rendszerek infrastruktúrája
- building management
- energy
- enviroment
- famring/precision aggrivulture

https://www.youtube.com/watch?v=_AlcRoqS65E

![iot stack](https://i.pinimg.com/originals/f8/bf/00/f8bf004cf42577b7fcdfe0c3de0daf87.png)

![iot edge functions](https://pbs.twimg.com/media/DguBB-FX0AAyY0H.jpg)

**Táv medicína:**
- [Microsoft HealthVault](https://www.microsoft.com/en-us/industry/health/microsoft-cloud-for-healthcare?rtc=1) betegek, orvosok közötti interakció, fejlődő országokban több helyen bevezetve, az otthoni egészségügyi eszközök gyártóit is bevonták, így egyból akár az eszközről feljuthat az információ a rendszerbe
- https://yourlifeyourdata.com/ 
- https://doktor24.hu/
- Adatgyűjtésre Google Health indult, ahol a beteg beadta milyen adatai vannak és azzal BigData elemzéseket lehet végrehajtani, meg lehet osztani a flehasználók (orvos-beteg) között.
- Lydia

Fájl típusúk összehasonlítása: ![fily types](https://ni.scene7.com/is/image/ni/Compare_Table_20090626160253?scl=1)

Struktúrált bináris fájl: [TDMS](https://www.wiresmithtech.com/articles/what-is-a-tdms-file/)

IoT menegment tool: https://thingsboard.io/

szenzor menedszment: https://temboo.com

- free szerver agent: https://www.oetiker.ch/en/oss/projects/ ; http://oss.oetiker.ch/mrtg/download.en.html ; 
- más megoldások: Temboo, Xively, 

## Hol tároljuk az adatot?
Végberendezésnél: 
- gyorsan hozzáférhető
- nyers adat
- adattöredékek
- sokszr lokális

központi:
- hozzáférhető
- teljes adatstrukktúra
- feldolgozott adat

adatküldési problémák:
- sebesség
- adat méret

Adattárolás:
- adat tömörítés
  - veszteséges 
  - veszteségmentes
  - bináris
- redukció
  - redundancia meghatározása
  - redundancia csökkentése
    - időbéylegek törlése
  - mennyiség csökkentése
    - x idő után elévülés
  - többszintű adattárolás:
    - lassabb - nagyobb
    - gyorsabb - kisebb
  - adatok titkosságának garantálása  

## rendszer távfelügyleet lépései
- SNMP
  - Az SNMP a Simple Network Management Protocol, azaz az egyszerű hálózat menedzsment protokoll rövidítése. A TCP/IP család része, az IETF hozta létre. Hálózatra kötött eszközök vezérlését, adatainak lekérdezését szolgálja.
  - *pl:*
    - *Nagios: alkalmas aktív hálózati eszközök, illetve szerverek monitorozására.* 
    - *HP OpenView: drága, már nem önlló termék.*
    - *Jopr: Vállalati szoftver menedzsment megoldás JBoss rendszerekhez.*
    - *RHQ: felxibilis plug-in rendszerű menedzsment szolgáltatás.*
- MIB-ek
  - Az SNMP protokollt kifejezetten bővíthetőre tervezték. Ezt a MIB-ek (management information base) segítségével érik el. 
  - Egy MIB bizonyos eszközök által használt speciális tulajdonságokat ír le.
  - Az egyes tulajdonságokat hierarchikus rendben elhelyezett objektumok reprezentálják. 
  - Az objektumoknak a hierarchiában való elhelyezkedése biztosít egyedi azonosítót. 
 

# fogalmak2
1.	CRC - checksum https://en.wikipedia.org/wiki/Cyclic_redundancy_check 
2.	CSMA/CD - az eszköz érzékeli az ütközést és vár; adás közben esetlegesen bekövetkező ütközést érzékeli és abbahagyja az adást. Régi ethernet protokoll.
3.	CSMA/CA - az állomás jelentkezik, amire választ kap ahhoz hogy adhasson; a vivőt érzékelve a saját forgalomtovábbításának megkezdését véletlenszerű idővel eltolja. Ez akkor lehet hasznos, ha feltételezhetjük, hogy a közeg kiürülésére több csomópont is várakozik. Ma is használta WIFI LAN-on
4.	M2M - A Machine-to-Machine ([M2M](https://www.youtube.com/watch?v=pPIC7gJIW8I&list=PLmpB0PK0w9EBDDJyyROgrSgy1XyitJfJd&index=2)) technológia olyan adatáramlást jelent, mely emberi közreműködés nélkül, gépek között zajlik. A kommunikáció minden olyan gép között létrejöhet, amely a megfelelő technológiával van ellátva ahhoz, hogy bekapcsolható legyen a rendszerbe. Mivel hatalmas adatmennyiséget kell a folyamat során értelmezni és tárolni, az M2M olyan fejlődő technológiákra támaszkodik, mint a felhőalapú számítástechnika vagy a Big Data elemzés. Alkalmazható: Gépek távfelügyelete, Aktuális állapot figyelése, Automatizálás és folyamat optimalizálás, Kritikus helyzetek észlelése. https://www.telekom.hu/uzleti/szolgaltatasok/egyeb-szolgaltatasok/m2m 
5.	WEP - elavult wifi titkosítási módszer https://en.wikipedia.org/wiki/Wired_Equivalent_Privacy
6.	WPA - 2004-ig használt wifi security protokol: https://en.wikipedia.org/wiki/Wi-Fi_Protected_Access
7.	WPA2 - 2004-2018 között érvényes wifi security protokol. https://en.wikipedia.org/wiki/Wi-Fi_Protected_Access#WPA2
8.	WiFi - mikrohullámú vezeték nélküli hálózati átvitel https://hu.wikipedia.org/wiki/Wi-Fi
9.	MAC - a network interface controller saját egyedi azonosítója https://en.wikipedia.org/wiki/MAC_address
10.	Access Point - hálózat hozzáférési pont, wifi vagy lan pl
11.	vivő érzékelés - Figyeljük a vivő médiumot (carrier), hogy szabad-e, mielőtt adatot küldünk CSMA-CSMA/CD-CSMA/CA következik belőle https://people.inf.elte.hu/lukovszki/Courses/09NWI/nwI07s4.pdf
12.	pozitív nyugta - Minden egyes elküldött csomaghoz tartozó ACK visszajelzése a teljes csomag átküldéséről, ilyen van a TCP protokollnál is https://hu.wikipedia.org/wiki/Transmission_Control_Protocol#Nyugt%C3%A1z%C3%A1s
13.	DOS támadás - túlterheléses támadás amit nem ugyanaz mint amit Marika néni intéz a vakcináztatási időpontra jelentkezéskor https://en.wikipedia.org/wiki/Denial-of-service_attack
14.	SSID - wifi hálózat azonosítója, "neve"
15.	MAC cím szűrés - csak előre betáplált hálózati azonosítóval rendelkező gépeket fogad el a hálózatra való jelentkezéskor https://en.wikipedia.org/wiki/MAC_filtering
16.	AES - az ezredfordulón elfogadott blokk eltolásos tikosíási módszer, brute force támadással még nem törték fel publikusan, de az "erőssége" függ a választott kulcs hosszától https://en.wikipedia.org/wiki/Advanced_Encryption_Standard
17.	BR/EDR - Bluetooth Basic Rate/Enhanced Data Rate - designed for low power operation and also leverages a robust Adaptive Frequency Hopping approach, transmitting data over 79 channels
18.	BLE - bluetooth low energy, kis adatok átküldésére, kis energiafogyasztás mellett, de sok lehetőséggel https://github.com/gabboraron/szenzormodularitasok#bluetooth
19.	FDMA - sávszél megosztás, tipikusan pl kábelTV szolgáltatásnál; [FDMA is the process of dividing one channel or bandwidth into multiple individual bands, each for use by a single user. Each individual band or channel is wide enough to accommodate the signal spectra of the transmissions to be propagated. The data to be transmitted is modulated on to each subcarrier, and all of them are linearly mixed together.](https://www.electronicdesign.com/technologies/communications/article/21802209/electronic-design-fundamentals-of-communications-access-technologies-fdma-tdma-cdma-ofdma-and-sdma)
20.	TDMA - [egy csatornán több felhasználó ugynazzal a frekvenciával de saját üzentet küldhet ](https://en.wikipedia.org/wiki/Time-division_multiple_access#:~:text=Time%2Ddivision%20multiple%20access%20(TDMA,using%20its%20own%20time%20slot.)
21.	Bluetooth energia osztály - a különböző bluetooth technogiák osztályozása, a magasabb értékűnek alacsonyabb a hatótávja. https://hu.wikipedia.org/wiki/Bluetooth
22.	PAN - personal area ntework
23.	HAN - home area network
24.	LAN - local area network
25.	NAN -  near-me network, or a network of devices informally connected by their proximity to one another. An example of this could be a business meeting in which various colleagues are sitting at the same conference table, sharing files to one another’s devices. 
26.	MAN - metropolitan area network
27.	WAN - wide area network - internet
28.	RAN - regional area network. This is a large network like one made by an ISP
29.	[Chirp](https://github.com/gabboraron/szenzormodularitasok#chirp) pulse - 
30.	LTE - Long Term Evolution - It's a standard for 4G wireless transmission data, the fourth generation of mobile network technology 4G LTE networks are the next generation from the existing 3G networks 
31.	5G - több antenna, más szögekben => nagyobb lefedettség; kevesebb használt rész => nagyobb sávszél https://ilearningx.huawei.com/portal/courses/course-v1:HuaweiX+EBGTC00000410+Self-paced/about
32.	LPWAN - low-power wide-area network - llow long-range communications at a low bit rate among things (connected objects), such as sensors operated on a battery. https://en.wikipedia.org/wiki/LPWAN 
33.	ED (End Device) - a mérőoszlop kinn a földön https://www.itwissen.info/Endgeraet-end-device-ED.html
34.	BS (Base Station) -  a radio receiver/transmitter that serves as the hub of the local wireless network, and may also be the gateway between a wired network and the wireless network. It typically consists of a low-power transmitter and wireless router. - https://en.wikipedia.org/wiki/Base_station#:~:text=In%20the%20area%20of%20wireless,power%20transmitter%20and%20wireless%20router.
35.	SIGFOX - [órai anyag](https://github.com/gabboraron/szenzormodularitasok#sigfox); Sigfox is rolling out the first global 0G network to listen to billions of objects broadcasting data, without the need to establish and maintain network connections. This unique approach in the world of wireless connectivity, where there is no signaling overhead, a compact and optimized protocol, and where object share not attached to the network. https://www.sigfox.com/en/what-sigfox/technology
36.	LoRa - low-power wide-area network; based on spread spectrum modulation techniques derived from chirp spread spectrum (CSS) technology
37.	LoRaWAN - LoRaWAN is a cloud-based medium access control (MAC) layer protocol but acts mainly as a network layer protocol for managing communication between LPWAN gateways and end-node devices as a routing protocol, maintained by the LoRa Alliance.
38.	Okos város - dugó elárító mi vezéreltközlekedési rendszer, okos kukák, stb stb stb pl: Szongdo
39.	M2M
40.	H2M - huamn to machine
41.	H2H - human to human
42.	TDMS - [Struktúrált bináris fájl](https://www.wiresmithtech.com/articles/what-is-a-tdms-file/)
43.	JSON - JavaScript Object Notation)
44.	XML  - Extensible Markup Language



 
