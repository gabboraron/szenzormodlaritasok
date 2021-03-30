# szenzormodalitások

- [What is a smart city](https://www.youtube.com/watch?v=Br5aJa6MkBc)


**Tárgyköveelmény:**
- 2 zh - vagy vizsga
- önálló féléves feladat


## szenzorok csoportosísása mérendő mennyisé alapján
- mechanikai érzékelők
- termikus mennyiségek
- elektromos és mágneses mennyiségek
- élettani paraméterek

biológia jellemzők mérésére:
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
multispektrrális képek a mezőgazdaásgról megadja a kukorica stressz szintjét, szárasság stb szintjét
- [RTK](https://en.wikipedia.org/wiki/Real-time_kinematic) használata
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
> - sok modlaitás
> - mintavételezési idők problámja ->sok adat
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

![wifisec](https://pbs.twimg.com/media/DF6XjSeXkAAvbUo.jpg)

- csma/ca - az állomás jelentkezik, amire választ kap ahhoz hogy adhasson
- csma/cd - az eszköz érzékeli az ütközést és vár 

wifi jelenlegi titkosítása 2018 óta WPA3

#### bluetooth
![bluetoth history](https://miro.medium.com/max/4000/1*_GjhWQieYTUl_2mbTehkJQ.png)

*könnyen hackelhető*

- 3.0 -ban a pan hálózatot kinyitotátk egy hálózati hozzáférésre mert beleillesztették a wifi protokolt
- 4.0 -ban low energy protokollt adtak bele
- 4.2 - ben IoT támogatást és IPv6 támogatást és titkosítást kapott
- 5 -ben 4Xtávolság és 8Xsebességre növelte a low energy megoldásokat
- most az 5.3-nál járunk, 243 méteres távolságra szól
  - 1 master 7 eszközt szolgál ki, és több százat alvó állapotban

**basic rate**
- BR: frekvenciamodulálásst használ, 1 tick 302.5 us
- LowEnergy: 1Mb/s

![brle](https://www.researchgate.net/profile/Karen-Scarfone/publication/329972964/figure/tbl2/AS:708926916030464@1546032756454/2-Key-Differences-Between-Bluetooth-BR-EDR-and-LE.png)

![howitworks](https://www.researchgate.net/profile/Ee-May-Fong/publication/259246800/figure/fig5/AS:297112509140993@1447848550198/Bluetooth-communication-between-the-transmitter-and-mobile-devices.png)

#### ant/ant+

- fitness eszközökhöz használt.
![ant](https://www.researchgate.net/profile/Nadeem-Mehmood/publication/285510534/figure/fig1/AS:367752901611520@1464690532770/hArmor-System-Modular-Architecture_Q320.jpg)![ant+](https://lh3.googleusercontent.com/proxy/ZoCFi0-uQOMWuHYv3GADWOMEjuUR6smHNo7HJErJR8O0VyOyBACHgx4S3X7aAz_ucoJFRNtxqIEXsn-Kk0MnpwlX22zflmhCkzmtQs90Bu3xfChtIQnC_AYzHwnA)

#### zigbee
okosházakban használt technológia
- 100m - ig
- 250kbps
- ism sávon: nem kell hozzá külön frekvenciengedély hogy használjuk.

## HF: megnézni és leküldeni, hogy a telefon milyen vezetkénélküli kapcsolatokra képes

#### 802.11.ah
- 1 km
- 40 mbps

#### nfc
-10 cm
424 kbps

#### long range uhf
- még minidg ism
- extrém esetben yagi antennákkal akár 160 km-is elérhető.
- frekvenciasáv: 433 MHz
- nagy hatótávolságú dronvezérléshez alklamas lehet

#### dash7 
- félkatonai felhasználása van
- alacsony a fogyasztása
- kb 1km a távolság
- civil: CO2 figyelés
- jól megy át vizen

#### UWB
- vezeték nélküli továbbítás
- szabványosítás és negedélyeztetés alatt áll
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
