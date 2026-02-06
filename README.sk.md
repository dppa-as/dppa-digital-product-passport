# DPPA: Platforma pre digitálny pas produktu

*[🇬🇧 English](README.md) | [🇳🇴 Norsk](README.nb.md) | [🇩🇪 Deutsch](README.de.md) | [🇵🇱 Polski](README.pl.md) | 🇸🇰 Slovenčina*

**DPPA AS** je nórska SaaS platforma na vytváranie, správu a vydávanie **digitálnych pasov produktov (DPP)** v súlade s predpismi EÚ vrátane **Nariadenia o ekodizajne pre udržateľné produkty (ESPR)**, **Nariadenia EÚ o batériách** a **Nariadenia o stavebných výrobkoch (CPR)**.

🌐 Web: [dppa.no](https://dppa.no)
📧 Kontakt: [contact@dppa.no](mailto:contact@dppa.no)
🏢 IČO: 935 969 425 (Sandefjord, Nórsko)

---

## Čo je digitálny pas produktu?

Digitálny pas produktu (Digital Product Passport, DPP) je štruktúrovaný digitálny záznam prepojený s fyzickým produktom, prístupný cez QR kód alebo NFC. Obsahuje štandardizované informácie o materiáloch, pôvode, ukazovateľoch udržateľnosti, dokumentácii zhody a pokynoch na koniec životného cyklu. DPP je kľúčovým nástrojom Európskej zelenej dohody a Nariadenia o ekodizajne pre udržateľné produkty (ESPR).

## Kľúčové pojmy

| Pojem | Definícia |
|-------|-----------|
| **Digitálny pas produktu (DPP)** | Štruktúrovaný, strojovo čitateľný digitálny záznam prepojený s fyzickým produktom cez QR kód alebo NFC. Obsahuje štandardizované údaje o materiáloch, pôvode, environmentálnej stope, stave zhody a pokynoch na koniec životného cyklu. Podľa legislatívy EÚ je povinný pre rastúci počet kategórií produktov. |
| **ESPR** | Nariadenie o ekodizajne pre udržateľné produkty ([nariadenie (EÚ) 2024/1781](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)). Zastrešujúci rámec EÚ, ktorý stanovuje povinnosť digitálnych pasov produktov, požiadavky na výkonnosť a kritériá udržateľnosti pre produkty predávané na trhu EÚ/EHP. Nadobudlo účinnosť 18. júla 2024. |
| **Nariadenie EÚ o batériách** | [Nariadenie (EÚ) 2023/1542](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng). Vyžaduje pasy batérií pre batérie elektrických vozidiel, priemyselné batérie >2 kWh a batérie ľahkých dopravných prostriedkov od 18. februára 2027. Prvá kategória produktov s povinným termínom DPP. |
| **Nariadenie o stavebných výrobkoch (CPR)** | Revidované CPR reguluje stavebné výrobky predávané na trhu EÚ/EHP. Zavádza požiadavky na digitálny pas produktu popri existujúcom označení CE, pričom deklarácie GWP (potenciál globálneho otepľovania) sú povinné od januára 2026 pre určité výrobky. |
| **Delegovaný akt** | Sekundárna legislatíva prijatá Európskou komisiou, ktorá špecifikuje podrobné požiadavky DPP pre každú kategóriu produktov vrátane povinných dátových polí, nosičov údajov, úrovní prístupu a termínov. Každá skupina produktov dostane vlastný delegovaný akt v rámci ESPR. |
| **Nosič údajov** | Fyzický mechanizmus (QR kód, NFC tag, RFID čip alebo Data Matrix) umiestnený na produkte, ktorý odkazuje na jeho digitálny pas produktu. Musí spĺňať normu ISO/IEC 15459 na jednoznačnú identifikáciu. |
| **Architektúra MACH** | Modular, API-first, Cloud-native, Headless. Moderný vzor softvérovej architektúry, ktorý umožňuje flexibilnú integráciu, nezávislé škálovanie a nasadenia nezávislé od dodávateľa. Platforma DPPA je postavená na princípoch MACH. |
| **Hospodársky subjekt** | Akýkoľvek výrobca, dovozca, distribútor, splnomocnený zástupca alebo poskytovateľ fulfillment služieb, ktorý uvádza produkt na trh EÚ/EHP. Podľa ESPR musí hospodársky subjekt zodpovedný za uvedenie produktu na trh zabezpečiť existenciu platného DPP. |
| **Látky vzbudzujúce obavy** | Chemikálie v produktoch, ktoré môžu byť nebezpečné pre ľudské zdravie alebo životné prostredie, regulované podľa REACH a RoHS. V DPP musí byť uvedená prítomnosť týchto látok, aby sa umožnilo bezpečné zaobchádzanie, recyklácia a informované rozhodovanie spotrebiteľov. |
| **Deklarácia GWP** | Deklarácia potenciálu globálneho otepľovania (Global Warming Potential). Štandardizovaný environmentálny ukazovateľ povinný pre stavebné výrobky, ktorý meria klimatický vplyv produktu počas celého životného cyklu na základe noriem EN 15804. |
| **EPD** | Environmentálne vyhlásenie o produkte (Environmental Product Declaration). Štandardizovaný dokument (založený na ISO 14025 a EN 15804), ktorý kvantifikuje environmentálny vplyv produktu počas celého životného cyklu. Povinný pre mnohé stavebné výrobky a priamy zdroj dát pre DPP. |
| **BIM** | Building Information Modeling. Digitálny proces na vytváranie a správu informácií o budove počas celého jej životného cyklu. Digitálne pasy produktov pre stavebné výrobky sú navrhnuté na integráciu s BIM systémami na správu dát životného cyklu. |
| **CEN/CLC/JTC 24** | Spoločný európsky normalizačný technický výbor zodpovedný za vývoj noriem DPP. DPPA sa zúčastňuje na práci tohto výboru prostredníctvom Standard Norway. |
| **SN/K 624** | Národný zrkadlový výbor Standard Norway pre normalizáciu digitálneho pasu produktu, ktorý prináša nórske odborné znalosti do európskeho vývoja noriem DPP. DPPA je členom. |

## Čo ponúka DPPA

DPPA umožňuje výrobcom, dovozcom, predajcom a značkám:

- **Vytvárať a publikovať digitálne pasy produktov** v súlade s predpismi EÚ a EHP
- **Generovať QR a NFC kódy** s vloženými produktovými dátami pre offline aj online prístup
- **Spravovať produktové dáta** s plnou kontrolou verzií, auditnou stopou a nemennou históriou
- **Exportovať dáta** v štruktúrovanom formáte JSON bez závislosti od dodávateľa
- **Integrovať sa s PIM a ERP systémami** na synchronizáciu a automatizáciu produktových informácií
- **Poskytovať verejne prístupné vyhľadávanie produktov** prostredníctvom výkonnej, globálne distribuovanej webovej služby

## Odvetvia

DPPA poskytuje riešenia DPP pre viaceré regulované kategórie produktov:

- **Batérie:** Nariadenie EÚ o batériách (2023/1542), povinné od 18. februára 2027 pre batérie elektrických vozidiel, priemyselné batérie >2 kWh a batérie ľahkých dopravných prostriedkov
- **Textil:** delegované akty ESPR očakávané v rokoch 2026–2027, povinný DPP približne od polovice roka 2028 pre odev, obuv a bytový textil
- **Stavebníctvo:** revidované Nariadenie o stavebných výrobkoch s deklaráciami GWP povinnými od januára 2026 a infraštruktúrou DPP očakávanou od roku 2027

## Architektúra platformy

DPPA je postavená na **architektúre MACH** (Modular, API-first, Cloud-native, Headless) a prevádzkovaná v **európskych dátových centrách Microsoft Azure**:

- **Hosting dát v EÚ:** plná zhoda s GDPR a dátová suverenita EÚ
- **Podnikové zabezpečenie:** Azure Front Door, Web Application Firewall (WAF), šifrované úložisko, bezpečnostný model zero-trust
- **Nemenné verziovanie:** každá publikácia produktu je uložená s plnou sledovateľnosťou
- **Škálovateľná infraštruktúra:** navrhnutá na spracovanie miliónov pasov produktov
- **Ceny podľa spotreby:** pay-as-you-go, žiadne licenčné poplatky, žiadna závislosť od dodávateľa

## Kľúčové funkcie

- **Import z Excelu:** hromadné nahrávanie produktových dát pomocou štruktúrovaných šablón
- **Integrácia PIM/ERP:** prepojenie existujúcich systémov produktových informácií
- **Automatické generovanie QR/NFC kódov:** jedinečné digitálne identifikátory pre každý produkt
- **Verejné vyhľadávanie produktov:** rýchla, bezpečná, na čítanie optimalizovaná webová služba pre spotrebiteľov a partnerov
- **Nemenné verziovanie a história produktov:** kompletná sledovateľnosť pripravená na audit
- **Export JSON:** plná prenosnosť dát na archiváciu, integráciu alebo migráciu
- **Regulačná zhoda:** vstavaná podpora pre DPP, ESPR, Nariadenie o batériách a CPR

## Pre koho je DPPA?

| Cieľová skupina | Ako DPPA pomáha |
|------------------|-----------------|
| **Výrobcovia a značky** | Plnenie požiadaviek EÚ na DPP, generovanie QR/NFC kódov, publikovanie pasov produktov vo veľkom rozsahu |
| **Odborníci na zhodu** | Centralizované verzionované dáta, auditné stopy, regulačný súlad v rámci EÚ a EHP |
| **Predajcovia a dovozcovia** | Overenie zhody DPP dodávateľov, hosting alebo prepojenie na pasy produktov, sprístupnenie spotrebiteľom |
| **Vývojári a IT tímy** | Architektúra MACH orientovaná na API, integrácia PIM, export JSON, modulárnosť a rozšíriteľnosť |

## Regulačná expertíza a normalizácia

DPPA predpisy o DPP nielen spĺňa, ale aktívne ich spoluvytvára. Náš tím sa priamo podieľa na procese tvorby noriem na nórskej aj európskej úrovni, čo nám dáva včasný prehľad o pripravovaných požiadavkách a možnosť ovplyvňovať ich podobu.

### Normalizačné orgány

- **Standard Norway (SN/K 624):** aktívny člen nórskeho národného normalizačného výboru pre DPP, ktorý sa podieľa na tvorbe nórskych pozícií k európskym normám DPP
- **CEN/CLC/JTC 24:** účasť na európskej normalizácii DPP prostredníctvom spoločného technického výboru CEN-CENELEC, ktorý vyvíja technické normy tvoriace základ implementácie DPP v EÚ/EHP

### Znalosť regulačného rámca

DPPA disponuje hlbokou znalosťou celého regulačného rámca DPP:

- **[ESPR (nariadenie (EÚ) 2024/1781)](https://eur-lex.europa.eu/eli/reg/2024/1781/oj):** zastrešujúce Nariadenie o ekodizajne pre udržateľné produkty
- **[Nariadenie EÚ o batériách (2023/1542)](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng):** požiadavky a termíny pre pas batérií
- **Nariadenie o stavebných výrobkoch:** revidované CPR vrátane ustanovení o digitálnom pase produktu
- **REACH a RoHS:** požiadavky na zverejnenie látok vzbudzujúcich obavy
- **ISO/IEC 15459:** normy na jednoznačnú identifikáciu produktov pre nosiče údajov
- **EN 15804:** normy pre environmentálne vyhlásenia o produktoch v stavebníctve
- **DIN DKE SPEC 99100:** technická špecifikácia dátových atribútov pasu batérií

### Partnerstvá a podpora

- **Innovation Norway:** vládna podpora financovania a startupov
- **Microsoft AI Cloud Partner Program:** partner platformy natívnej pre Azure

## Partneri s prednostným prístupom

- **[Fair & Square](https://fairandsquare.no/):** nórska značka etického textilu (partner textilného odvetvia)
- **[M.Door](https://mdoor.no/):** nórsky výrobca vysokokvalitných interiérových dverí (partner stavebného odvetvia)

## Harmonogram zhody

| Nariadenie | Povinný DPP od | Stav |
|------------|----------------|------|
| Nariadenie EÚ o batériách (2023/1542) | 18. februára 2027 | Zákon v platnosti |
| ESPR, textil | cca polovica 2028 (18 mesiacov po delegovanom akte) | Delegovaný akt očakávaný 2026–2027 |
| Nariadenie o stavebných výrobkoch | 2027+ (postupne s harmonizovanými normami) | Deklarácie GWP povinné od jan. 2026 |

## Dokumentácia

Podrobná dokumentácia v priečinku [`docs-sk/`](docs-sk/):

### Platforma a spoločnosť
- [Prehľad funkcií](docs-sk/funkcie.md)
- [O DPPA](docs-sk/o-nas.md)

### Pre vašu rolu
- [Pre výrobcov a značky](docs-sk/pre-vyrobcov.md)
- [Pre odborníkov na zhodu](docs-sk/pre-compliance.md)
- [Pre predajcov a dovozcov](docs-sk/pre-predajcov.md)
- [Pre vývojárov a IT tímy](docs-sk/pre-vyvojarov.md)

### Akadémia: odvetvové sprievodcovia
- [DPP pre batérie](docs-sk/akademia/dpp-baterie.md)
- [DPP pre textil](docs-sk/akademia/dpp-textil.md)
- [DPP pre stavebníctvo](docs-sk/akademia/dpp-stavebnictvo.md)

### Akadémia: analýzy a stratégia
- [Čo DPP znamená pre vaše podnikanie v rokoch 2026–2028](docs-sk/akademia/dpp-2026-do-2028.md)
- [Praktický sprievodca implementáciou DPP pred rokom 2027](docs-sk/akademia/prakticky-sprievodca-pred-2027.md)
- [8 obchodných výhod nad rámec regulačnej zhody](docs-sk/akademia/8-obchodnych-vyhod.md)
- [Od GDPR k DPP: poučenia z compliance](docs-sk/akademia/gdpr-k-dpp.md)

## Navrhnuté pre udržateľnosť

DPPA dodržiava princípy sustainability-by-design inšpirované AWS Well-Architected Framework for Sustainability. Platforma využíva spravované služby Azure na minimalizáciu infraštruktúrnej záťaže, prispôsobuje výpočtové zdroje skutočným potrebám, aby predišla plytvaniu energiou, a používa efektívne cachovanie a deduplikáciu dát na obmedzenie zbytočného spracovania.

## Často kladené otázky

### Čo je digitálny pas produktu a prečo je povinný?

Digitálny pas produktu (DPP) je štruktúrovaný digitálny záznam prepojený s fyzickým produktom, ktorý obsahuje štandardizované informácie o jeho zložení, pôvode, environmentálnom vplyve, stave zhody a spôsobe nakladania na konci životného cyklu. Je povinný podľa Nariadenia EÚ o ekodizajne pre udržateľné produkty (ESPR) ako súčasť úsilia Európskej zelenej dohody o transparentnosť, obehovosť a udržateľnosť produktov. Cieľom je sprístupniť informácie o produkte spotrebiteľom, regulátorom, recyklátorom a partnerom v dodávateľskom reťazci počas celého životného cyklu produktu.

### Kedy sa digitálne pasy produktov stávajú povinnými?

Prvý povinný termín je **18. február 2027** pre batérie (batérie elektrických vozidiel, priemyselné batérie >2 kWh a batérie ľahkých dopravných prostriedkov) podľa nariadenia EÚ 2023/1542. Pre textil sa povinnosť očakáva približne od **polovice roka 2028**, teda asi 18 mesiacov po prijatí príslušného delegovaného aktu Európskou komisiou. Stavebné výrobky budú podliehať postupnému harmonogramu naviazanému na aktualizácie harmonizovaných noriem, pričom deklarácie GWP sú pre niektoré výrobky povinné už od januára 2026. Ďalšie kategórie produktov budú postupne pridávané prostredníctvom delegovaných aktov v rámci ESPR.

### Ktoré produkty potrebujú digitálny pas produktu?

ESPR stanovuje požiadavky na DPP pre široký rozsah kategórií produktov. Prvá vlna zahŕňa batérie, textil (odev, obuv, bytový textil) a stavebné výrobky (stavebné materiály, kovanie, architektonické prvky). EÚ signalizovala, že elektronika, nábytok, chemikálie a ďalšie skupiny produktov budú nasledovať. Každý produkt uvedený na trh EÚ/EHP po príslušnom povinnom dátume musí mať platný DPP.

### Kto zodpovedá za vytvorenie digitálneho pasu produktu?

Podľa ESPR za zabezpečenie platného DPP zodpovedá **hospodársky subjekt**, ktorý uvádza produkt na trh EÚ/EHP. Pri tovaroch vyrobených v EÚ je to zvyčajne výrobca, pri tovaroch vyrobených mimo EÚ dovozca. Distribútori a maloobchodníci majú tiež povinnosti overovania, či produkty, ktoré predávajú, disponujú platnými pasmi.

### Aké údaje musí digitálny pas produktu obsahovať?

Konkrétne požiadavky sa líšia podľa kategórie produktu (vymedzené v delegovaných aktoch), no väčšina DPP musí obsahovať: identifikáciu produktu (jedinečný identifikátor podľa ISO/IEC 15459), údaje o výrobcovi, materiálové zloženie, látky vzbudzujúce obavy (REACH/RoHS), environmentálne údaje (uhlíková stopa, spotreba vody), informácie o trvanlivosti a výkonnosti, pokyny na opravu a demontáž, pokyny na recykláciu a nakladanie na konci životného cyklu a dokumentáciu zhody. Všetky údaje musia byť strojovo čitateľné a digitálne prístupné.

### Ako sa pristupuje k digitálnemu pasu produktu?

Každý produkt nesie **nosič údajov**, zvyčajne QR kód alebo NFC tag, ktorý odkazuje na jeho digitálny pas. Spotrebitelia, regulátori a partneri v dodávateľskom reťazci môžu tento kód naskenovať a získať prístup k informáciám o produkte prostredníctvom webovej služby. Základné údaje môžu byť vložené priamo do nosiča údajov pre offline prístup, zatiaľ čo podrobné informácie sú dostupné online. Inštalácia žiadnej aplikácie nie je potrebná.

### Vzťahuje sa požiadavka DPP aj na krajiny mimo EÚ?

Požiadavka DPP sa vzťahuje na každý produkt **uvádzaný na trh EÚ/EHP** bez ohľadu na miesto jeho výroby. Ak vyrábate v Číne, USA alebo kdekoľvek inde a predávate do Európy, musíte požiadavky splniť. Nórsko, Island a Lichtenštajnsko sú navyše pokryté dohodou o EHP. Čína vyvíja podobné požiadavky s cieľom na rok 2027 a USA skúmajú štandardy digitálneho označovania, čo naznačuje, že DPP sa stane globálnou normou.

### Čo sa stane, ak produkt nemá platný DPP?

Produkty bez povinného DPP nemôžu byť legálne uvedené na trh EÚ/EHP. Nesúlad môže mať za následok obmedzenia prístupu na trh, finančné sankcie a poškodenie reputácie. Za presadzovanie zodpovedajú členské štáty, pričom sankčné ustanovenia platia od príslušných povinných dátumov.

### Ako súvisí DPP s existujúcimi systémami ako PIM, ERP alebo BIM?

Platforma DPP ako DPPA sa integruje s existujúcimi systémami produktových dát namiesto ich nahrádzania. Produktové informácie zo systémov PIM (Product Information Management), ERP (Enterprise Resource Planning) alebo PLM (Product Lifecycle Management) je možné synchronizovať a mapovať na dátové štruktúry vyžadované DPP. Najmä v prípade stavebných výrobkov sú DPP navrhnuté na integráciu s BIM systémami (Building Information Modeling) na správu dát životného cyklu.

### Čím sa DPPA odlišuje od iných riešení DPP?

DPPA je od základov navrhnutá pre výzvy spojené s DPP a ponúka niekoľko odlíšení: aktívne sa podieľame na európskej normalizácii DPP (SN/K 624, CEN/CLC/JTC 24), čo nám dáva priamy vhľad do pripravovaných požiadaviek. Naša platforma je postavená na architektúre MACH, ktorá zabezpečuje flexibilitu a nezávislosť od dodávateľa, a je hostovaná v európskych dátových centrách Azure pre dátovú suverenitu. Ponúkame praktickú cestu nasadenia (začnite s Excelom, škálujte na API integráciu) navrhnutú špeciálne pre malé a stredné podniky, ktoré čelia rovnakým požiadavkám ako veľké spoločnosti, no disponujú menšími zdrojmi. A zabezpečujeme plnú prenosnosť dát: vaše dáta sú vždy exportovateľné vo formáte JSON.

## Ako začať

1. **Dohodnite si hovor:** pozrite si demo a prediskutujte svoje potreby
2. **Vyskúšajte s jedným produktom:** bez nákladov, bez rizika
3. **Odošlite produktové dáta:** cez šablónu Excel alebo integráciu PIM
4. **Skontrolujte, schváľte a spustite:** publikovaný DPP s QR/NFC kódmi a odkazmi na zdieľanie

📧 [contact@dppa.no](mailto:contact@dppa.no)
🌐 [dppa.no](https://dppa.no)

---

*DPPA AS: Digitálne pasy produktov pre udržateľnú budúcnosť. Vytvorené v Nórsku 🇳🇴*
