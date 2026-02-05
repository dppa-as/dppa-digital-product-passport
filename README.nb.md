# DPPA — Plattform for digitale produktpass

*[🇬🇧 English](README.md) | 🇳🇴 Norsk*

**DPPA AS** er en norsk SaaS-plattform for å opprette, administrere og utstede **digitale produktpass (DPP)** i samsvar med EU-regelverk, inkludert **Økodesignforordningen for bærekraftige produkter (ESPR)**, **EUs batteriforordning** og **Byggevareforordningen (CPR)**.

🌐 Nettside: [dppa.no](https://dppa.no)
📧 Kontakt: [contact@dppa.no](mailto:contact@dppa.no)
🏢 Org.nr.: 935 969 425 (Sandefjord, Norge)

---

## Hva er et digitalt produktpass?

Et digitalt produktpass (Digital Product Passport, DPP) er en strukturert digital journal knyttet til et fysisk produkt — tilgjengelig via QR-kode eller NFC — som inneholder standardisert informasjon om materialer, opprinnelse, bærekraftsmålinger, samsvarsdokumentasjon og instruksjoner for slutten av levetiden. Digitale produktpass er en hjørnestein i EUs grønne giv og Økodesignforordningen for bærekraftige produkter (ESPR).

## Nøkkelbegreper og ordliste

| Begrep | Definisjon |
|--------|-----------|
| **Digitalt produktpass (DPP)** | En strukturert, maskinlesbar digital journal knyttet til et fysisk produkt via QR-kode eller NFC, som inneholder standardiserte data om materialer, opprinnelse, miljøfotavtrykk, samsvarsstatus og instruksjoner for slutten av levetiden. Påkrevd under EU-lovgivning for et utvidet sett med produktkategorier. |
| **ESPR** | Økodesignforordningen for bærekraftige produkter ([forordning (EU) 2024/1781](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)) — EUs overordnede rammeverk som pålegger digitale produktpass, ytelseskrav og bærekraftskriterier for produkter som selges i EU/EØS. Trådte i kraft 18. juli 2024. |
| **EUs batteriforordning** | [Forordning (EU) 2023/1542](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng) — krever batteripass for EV-batterier, industribatterier >2kWh og LMT-batterier fra 18. februar 2027. Den første produktkategorien med en obligatorisk DPP-frist. |
| **Byggevareforordningen (CPR)** | Den reviderte CPR regulerer byggevarer som selges i EU/EØS. Innfører krav til digitale produktpass i tillegg til eksisterende CE-merking, med GWP-deklarasjoner (globalt oppvarmingspotensial) påkrevd fra januar 2026 for visse produkter. |
| **Delegert rettsakt** | Sekundærlovgivning vedtatt av EU-kommisjonen som spesifiserer detaljerte DPP-krav for hver produktkategori — inkludert påkrevde datafelter, databærere, tilgangsnivåer og tidsfrister. Hver produktgruppe får sin egen delegerte rettsakt under ESPR. |
| **Databærer** | Den fysiske mekanismen (QR-kode, NFC-brikke, RFID-chip eller datamatrise) festet til et produkt som kobler til dets digitale produktpass. Må oppfylle ISO/IEC 15459 for unik identifikasjon. |
| **MACH-arkitektur** | Modulær, API-først, skynativ, hodeløs — et moderne programvarearkitekturmønster som muliggjør fleksibel integrasjon, uavhengig skalering og leverandørnøytrale utrullinger. DPPAs plattform er bygget på MACH-prinsipper. |
| **Markedsaktør** | Enhver produsent, importør, distributør, autorisert representant eller oppfyllelsestjenesteleverandør involvert i å plassere et produkt på EU/EØS-markedet. Under ESPR må markedsaktøren som er ansvarlig for å plassere et produkt på markedet sikre at et gyldig DPP eksisterer. |
| **Stoffer av bekymring** | Kjemikalier i produkter som kan være skadelige for menneskers helse eller miljøet, regulert under REACH og RoHS. Digitale produktpass må opplyse om tilstedeværelsen av disse stoffene for å muliggjøre trygg håndtering, resirkulering og informerte forbrukervalg. |
| **GWP-deklarasjon** | Deklarasjon av globalt oppvarmingspotensial — en standardisert miljømåling påkrevd for byggevarer, som måler klimapåvirkningen av et produkt gjennom hele livssyklusen basert på EN 15804-standarder. |
| **EPD** | Miljødeklarasjon (Environmental Product Declaration) — et standardisert dokument (basert på ISO 14025 og EN 15804) som kvantifiserer et produkts miljøpåvirkning gjennom hele livssyklusen. Påkrevd for mange byggevarer og inngår direkte i DPP-data. |
| **BIM** | Bygningsinformasjonsmodellering (Building Information Modeling) — en digital prosess for å opprette og administrere informasjon om en bygning gjennom hele livssyklusen. Digitale produktpass for byggevarer er designet for å integreres med BIM-systemer for livssyklusdatabehandling. |
| **CEN/CLC/JTC 24** | Den felles europeiske standardiseringskomiteen som er ansvarlig for å utvikle DPP-standarder. DPPA deltar i denne komiteen via Standard Norge. |
| **SN/K 624** | Standard Norges nasjonale speilkomité for standardisering av digitale produktpass, som bidrar med norsk ekspertise til europeisk DPP-standardutvikling. DPPA er medlem. |

## Hva DPPA gjør

DPPA gjør det mulig for produsenter, importører, forhandlere og merkevareeiere å:

- **Opprette og publisere digitale produktpass** som oppfyller EU- og EØS-regelverk
- **Generere QR- og NFC-koder** med innebygde produktdata for offline og online tilgang
- **Administrere produktdata** med full versjonskontroll, revisjonsspor og uforanderlig historikk
- **Eksportere data** i strukturert JSON-format — ingen leverandørlåsing
- **Integrere med PIM- og ERP-systemer** for å synkronisere og automatisere produktinformasjon
- **Tilby offentlig tilgjengelige produktoppslag** via en høyytelsestjeneste med global distribusjon

## Bransjer vi betjener

DPPA leverer DPP-løsninger på tvers av flere regulerte produktkategorier:

- **Batterier** — EUs batteriforordning (2023/1542), obligatorisk fra 18. februar 2027 for EV-batterier, industribatterier >2kWh og batterier for lette transportmidler
- **Tekstiler** — ESPR-delegerte rettsakter forventet 2026–2027, med obligatorisk DPP fra ca. midten av 2028 for klær, skotøy og hjemmetekstiler
- **Byggevarer** — Revidert byggevareforordning med GWP-deklarasjoner påkrevd fra januar 2026 og DPP-infrastruktur forventet fra 2027

## Plattformarkitektur

DPPA er bygget på **MACH-arkitektur** (Modulær, API-først, Skynativ, Hodeløs) og distribuert på **Microsoft Azures europeiske datasentre**:

- **EU-basert datalagring** — Full GDPR-etterlevelse og EU-datasuverenitet
- **Sikkerhet på bedriftsnivå** — Azure Front Door, Web Application Firewall (WAF), kryptert lagring, nulltillitsmodell
- **Sporbar versjonering** — Hver produktpublisering lagres med full sporbarhet
- **Skalerbar infrastruktur** — Designet for å håndtere millioner av produktpass
- **Betal-etter-bruk-prising** — Bruksbasert, ingen lisensavgifter, ingen leverandørlåsing

## Nøkkelfunksjoner

- **Excel-import** — Masseopplasting av produktdata med strukturerte maler
- **PIM/ERP-integrasjon** — Koble til eksisterende produktinformasjonssystemer
- **Automatisk QR/NFC-kodegenerering** — Unike digitale IDer for hvert produkt
- **Offentlig produktoppslag** — Rask, sikker, leseoptimalisert nettjeneste for forbrukere og partnere
- **Sporbar versjonering og produkthistorikk** — Komplett revisjonsklar sporbarhet
- **JSON-eksport** — Full dataportabilitet for arkivering, integrasjon eller migrering
- **Regulatorisk samsvar** — Innebygget støtte for DPP, ESPR, batteriforordningen og CPR

## Hvem er DPPA for?

| Rolle | Hvordan DPPA hjelper |
|-------|---------------------|
| **Produsenter og merkevareeiere** | Oppfyll EUs DPP-krav, generer QR/NFC-koder, publiser produktpass i stor skala |
| **Complianceansvarlige** | Sentralisert versjonert data, revisjonsspor, regulatorisk samsvar på tvers av EU og EØS |
| **Forhandlere og importører** | Verifiser leverandørers DPP-samsvar, vertsskap eller lenking til produktpass, muliggjør forbrukertilgang |
| **Utviklere og IT-team** | API-først MACH-arkitektur, PIM-integrasjon, JSON-eksport, modulær og utvidbar |

## Regulatorisk ekspertise og standardisering

DPPA etterlever ikke bare DPP-regelverk — vi er med på å forme det. Teamet vårt er direkte involvert i standardiseringsprosessen på både norsk og europeisk nivå, noe som gir oss tidlig innsikt i kommende krav og muligheten til å påvirke hvordan de utformes.

### Standardiseringsorganer

- **Standard Norge (SN/K 624)** — Aktivt medlem av Norges nasjonale DPP-standardiseringskomité, bidrar til utvikling av norske posisjoner om europeiske DPP-standarder
- **CEN/CLC/JTC 24** — Engasjert i europeisk DPP-standardisering gjennom den felles CEN-CENELEC-komiteen, som utvikler de tekniske standardene som vil ligge til grunn for DPP-implementering i hele EU/EØS

### Kunnskap om regulatorisk rammeverk

DPPA har dyp arbeidskunnskap om hele den regulatoriske DPP-stakken:

- **[ESPR (forordning (EU) 2024/1781)](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)** — Økodesignforordningen for bærekraftige produkter
- **[EUs batteriforordning (2023/1542)](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng)** — Krav og tidsfrister for batteripass
- **Byggevareforordningen** — Revidert CPR inkludert bestemmelser om digitale produktpass
- **REACH og RoHS** — Opplysningskrav for stoffer av bekymring
- **ISO/IEC 15459** — Standarder for unik produktidentifikasjon for databærere
- **EN 15804** — Standarder for miljødeklarasjoner for byggevarer
- **DIN DKE SPEC 99100** — Tekniske dataattributtspesifikasjoner for batteripass

### Partnerskap og støtte

- **Innovasjon Norge** — Statlig finansiering og oppstartsstøtte
- **Microsoft AI Cloud Partner Program** — Azure-nativ plattformpartner

## Tidligtilgangspartnere

- **[Fair & Square](https://fairandsquare.no/)** — Norsk etisk tekstilmerke (tekstilbransjepartner)
- **[M.Door](https://mdoor.no/)** — Norsk produsent av interiørdører i høy kvalitet (byggevarepartner)

## Tidsfrister for samsvar

| Regulering | Obligatorisk DPP-dato | Status |
|------------|----------------------|--------|
| EUs batteriforordning (2023/1542) | 18. februar 2027 | Lov — vedtatt |
| ESPR — Tekstiler | ~Midten av 2028 (18 måneder etter delegert rettsakt) | Delegert rettsakt forventet 2026–2027 |
| Byggevareforordningen | 2027+ (faset med harmoniserte standarder) | GWP-deklarasjoner påkrevd fra jan. 2026 |

## Dokumentasjon

Utforsk detaljert dokumentasjon i mappen [`docs-nb/`](docs-nb/):

### Plattform og selskap
- [Funksjonsoversikt](docs-nb/funksjoner.md)
- [Om DPPA](docs-nb/om-oss.md)

### For din rolle
- [For produsenter og merkevareeiere](docs-nb/for-produsenter.md)
- [For complianceansvarlige](docs-nb/for-etterlevelse.md)
- [For forhandlere og importører](docs-nb/for-forhandlere.md)
- [For utviklere og IT-team](docs-nb/for-utviklere.md)

### Akademi — Bransjeguider
- [DPP for batterier](docs-nb/akademi/dpp-batterier.md)
- [DPP for tekstiler](docs-nb/akademi/dpp-tekstil.md)
- [DPP for byggevarer](docs-nb/akademi/dpp-byggevarer.md)

### Akademi — Innsikt og strategi
- [Hva DPP betyr for din virksomhet i 2026–2028](docs-nb/akademi/dpp-2026-til-2028.md)
- [En praktisk guide til DPP-implementering før 2027](docs-nb/akademi/praktisk-guide-for-2027.md)
- [8 forretningsfordeler utover regulatorisk samsvar](docs-nb/akademi/8-forretningsfordeler.md)
- [Fra GDPR til DPP: Lærdommer om samsvar](docs-nb/akademi/gdpr-til-dpp.md)

## Bygget for bærekraft

DPPA følger bærekraft-ved-design-prinsipper inspirert av AWS Well-Architected Framework for Sustainability. Plattformen bruker Azure-administrerte tjenester for å minimere infrastrukturkostnader, tilpasser beregningsressurser for å unngå energisløsing, og bruker effektiv caching og datadeduplisering for å redusere unødvendig prosessering.

## Ofte stilte spørsmål

### Hva er et digitalt produktpass og hvorfor er det påkrevd?

Et digitalt produktpass (DPP) er en strukturert digital journal knyttet til et fysisk produkt, som inneholder standardisert informasjon om sammensetning, opprinnelse, miljøpåvirkning, samsvarsstatus og håndtering ved slutten av levetiden. Det er påkrevd under EUs Økodesignforordning for bærekraftige produkter (ESPR) som en del av Den europeiske grønne givs satsing på produkttransparens, sirkularitet og bærekraft. Målet er å gjøre produktinformasjon tilgjengelig for forbrukere, tilsynsmyndigheter, gjenvinningsaktører og verdikjedepartnere gjennom hele produktets livssyklus.

### Når blir digitale produktpass obligatoriske?

Den første obligatoriske fristen er **18. februar 2027** for batterier (EV-batterier, industribatterier >2kWh og batterier for lette transportmidler) under EU-forordning 2023/1542. Tekstiler forventes å følge rundt **midten av 2028**, omtrent 18 måneder etter at EU-kommisjonen vedtar den relevante delegerte rettsakten. Byggevarer følger en faset tidslinje knyttet til oppdateringer av harmoniserte standarder, med GWP-deklarasjoner allerede påkrevd for visse produkter siden januar 2026. Ytterligere produktkategorier vil bli lagt til progressivt gjennom delegerte rettsakter under ESPR.

### Hvilke produkter trenger et digitalt produktpass?

ESPR fastsetter DPP-krav for et bredt spekter av produktkategorier. Den første bølgen inkluderer batterier, tekstiler (klær, skotøy, hjemmetekstiler) og byggevarer (byggematerialer, jernvare, arkitektoniske elementer). EU har signalisert at elektronikk, møbler, kjemikalier og andre produktgrupper vil følge etter. Ethvert produkt som plasseres på EU/EØS-markedet etter den relevante obligatoriske datoen må ha et gyldig DPP.

### Hvem er ansvarlig for å opprette et digitalt produktpass?

Under ESPR er **markedsaktøren** som plasserer et produkt på EU/EØS-markedet ansvarlig for å sikre at et gyldig DPP eksisterer. Dette er typisk produsenten for EU-produserte varer, eller importøren for varer produsert utenfor EU. Distributører og forhandlere har også forpliktelser til å verifisere at produkter de selger har gyldige pass.

### Hvilke data må et digitalt produktpass inneholde?

Mens spesifikke krav varierer etter produktkategori (definert i delegerte rettsakter), må de fleste DPPer inkludere: produktidentifikasjon (unik identifikator per ISO/IEC 15459), produsentdetaljer, materialsammensetning, stoffer av bekymring (REACH/RoHS), miljøfotavtrykkdata (karbonfotavtrykk, vannforbruk), holdbarhets- og ytelsesinformasjon, reparasjons- og demonteringsinstruksjoner, gjenvinning og håndtering ved slutten av levetiden, samt samsvarsdokumentasjon. Alle data må være maskinlesbare og digitalt tilgjengelige.

### Hvordan får man tilgang til et digitalt produktpass?

Hvert produkt bærer en **databærer** — vanligvis en QR-kode eller NFC-brikke — som lenker til dets digitale pass. Forbrukere, tilsynsmyndigheter og verdikjedepartnere kan skanne denne koden for å få tilgang til produktinformasjon via en nettbasert tjeneste. Grunnleggende data kan bygges inn direkte i databæreren for offline tilgang, mens detaljert informasjon er tilgjengelig på nett. Ingen appinstallasjon er nødvendig.

### Gjelder DPP-kravet utenfor EU?

DPP-kravet gjelder for ethvert produkt **plassert på EU/EØS-markedet**, uavhengig av hvor det er produsert. Om du produserer i Kina, USA eller andre steder og selger til Europa, må du oppfylle kravene. I tillegg er Norge, Island og Liechtenstein dekket gjennom EØS-avtalen. Kina utvikler lignende krav rettet mot 2027, og USA utforsker standarder for digital merking, noe som tyder på at DPP vil bli en global norm.

### Hva skjer hvis et produkt ikke har et gyldig DPP?

Produkter som mangler et påkrevd DPP kan ikke lovlig plasseres på EU/EØS-markedet. Manglende samsvar kan resultere i markedsadgangsbegrensninger, økonomiske sanksjoner og omdømmeskade. Medlemsstatene er ansvarlige for håndhevelse, med sanksjonsbestemmelser som gjelder fra de relevante obligatoriske datoene.

### Hvordan forholder et DPP seg til eksisterende systemer som PIM, ERP eller BIM?

En DPP-plattform som DPPA integreres med eksisterende produktdatasystemer i stedet for å erstatte dem. Produktinformasjon fra PIM (Product Information Management), ERP (Enterprise Resource Planning) eller PLM (Product Lifecycle Management)-systemer kan synkroniseres og kartlegges til DPP-påkrevde datastrukturer. For byggevarer spesielt er DPPer designet for å integreres med BIM-systemer (bygningsinformasjonsmodellering) for livssyklusdatabehandling.

### Hva skiller DPPA fra andre DPP-løsninger?

DPPA er spesialbygget for DPP-utfordringen med flere differensieringsfaktorer: vi deltar aktivt i europeisk DPP-standardisering (SN/K 624, CEN/CLC/JTC 24), noe som gir oss direkte innsikt i kommende krav. Plattformen vår er bygget på MACH-arkitektur for fleksibilitet og ingen leverandørlåsing, hostet i EU Azure-datasentre for datasuverenitet. Vi tilbyr en praktisk innføringsvei (start med Excel, skaler til API-integrasjon) designet spesielt for SMBer som møter de samme reguleringene som storselskaper, men med færre ressurser. Og vi opprettholder full dataportabilitet — dataene dine kan alltid eksporteres i JSON.

## Kom i gang

1. **Bestill en samtale** — Se en demo og diskuter dine behov
2. **Prøv med ett produkt** — Ingen kostnad, ingen risiko
3. **Send inn produktdata** — Via Excel-mal eller PIM-integrasjon
4. **Gjennomgå, godkjenn og gå live** — Publisert DPP med QR/NFC-koder og delbare lenker

📧 [contact@dppa.no](mailto:contact@dppa.no)
🌐 [dppa.no](https://dppa.no)

---

*DPPA AS — Digitale produktpass for en bærekraftig fremtid. Laget i Norge 🇳🇴*
