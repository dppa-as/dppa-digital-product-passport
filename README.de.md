# DPPA — Plattform für den Digitalen Produktpass

*[🇬🇧 English](README.md) | [🇳🇴 Norsk](README.nb.md) | 🇩🇪 Deutsch | [🇵🇱 Polski](README.pl.md)*

**DPPA AS** ist eine norwegische SaaS-Plattform zur Erstellung, Verwaltung und Ausstellung von **Digitalen Produktpässen (DPP)** — konform mit EU-Verordnungen wie der **Ökodesign-Verordnung für nachhaltige Produkte (ESPR)**, der **EU-Batterieverordnung** und der **Bauproduktenverordnung (CPR)**.

🌐 Website: [dppa.no](https://dppa.no)
📧 Kontakt: [contact@dppa.no](mailto:contact@dppa.no)
🏢 Org.-Nr.: 935 969 425 (Sandefjord, Norwegen)

---

## Was ist ein Digitaler Produktpass?

Ein Digitaler Produktpass (Digital Product Passport, DPP) ist ein strukturierter digitaler Datensatz, der mit einem physischen Produkt verknüpft ist — zugänglich über QR-Code oder NFC. Er enthält standardisierte Informationen zu Materialien, Herkunft, Nachhaltigkeitskennzahlen, Konformitätsnachweisen und Hinweisen zur Entsorgung. Der DPP ist ein zentrales Instrument des EU Green Deal und der Ökodesign-Verordnung für nachhaltige Produkte (ESPR).

## Zentrale Begriffe

| Begriff | Erklärung |
|---------|-----------|
| **Digitaler Produktpass (DPP)** | Ein strukturierter, maschinenlesbarer digitaler Datensatz, der über QR-Code oder NFC mit einem physischen Produkt verknüpft ist. Er enthält standardisierte Angaben zu Materialien, Herkunft, ökologischem Fußabdruck, Konformitätsstatus und Entsorgungshinweisen. Für immer mehr Produktkategorien gesetzlich vorgeschrieben. |
| **ESPR** | Die Ökodesign-Verordnung für nachhaltige Produkte ([Verordnung (EU) 2024/1781](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)) — der übergeordnete EU-Rahmen für Digitale Produktpässe, Leistungsanforderungen und Nachhaltigkeitskriterien für Produkte im EU-/EWR-Markt. In Kraft seit 18. Juli 2024. |
| **EU-Batterieverordnung** | [Verordnung (EU) 2023/1542](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng) — schreibt ab dem 18. Februar 2027 Batteriepässe für EV-Batterien, Industriebatterien >2 kWh und Leichtfahrzeug-Batterien vor. Erste Produktkategorie mit verbindlicher DPP-Frist. |
| **Bauproduktenverordnung (CPR)** | Die überarbeitete CPR regelt Bauprodukte im EU-/EWR-Markt. Führt Anforderungen an den Digitalen Produktpass neben der bestehenden CE-Kennzeichnung ein, mit GWP-Erklärungen (Treibhauspotenzial) ab Januar 2026 für bestimmte Produkte. |
| **Delegierter Rechtsakt** | Sekundärrecht der Europäischen Kommission, das die konkreten DPP-Anforderungen je Produktkategorie festlegt — einschließlich Pflichtdatenfeldern, Datenträgern, Zugriffsrechten und Fristen. Jede Produktgruppe erhält unter der ESPR einen eigenen delegierten Rechtsakt. |
| **Datenträger** | Das physische Medium (QR-Code, NFC-Tag, RFID-Chip oder Data Matrix), das am Produkt angebracht ist und auf dessen Digitalen Produktpass verweist. Muss ISO/IEC 15459 für die eindeutige Identifikation erfüllen. |
| **MACH-Architektur** | Modular, API-first, Cloud-native, Headless — ein modernes Software-Architekturprinzip für flexible Integration, unabhängige Skalierung und herstellerunabhängige Deployments. Die DPPA-Plattform basiert auf MACH-Prinzipien. |
| **Wirtschaftsakteur** | Jeder Hersteller, Importeur, Händler, Bevollmächtigte oder Fulfillment-Dienstleister, der ein Produkt im EU-/EWR-Markt in Verkehr bringt. Unter der ESPR muss der verantwortliche Wirtschaftsakteur sicherstellen, dass ein gültiger DPP vorliegt. |
| **Besorgniserregende Stoffe** | Chemikalien in Produkten, die für Mensch oder Umwelt gefährlich sein können und unter REACH und RoHS reguliert sind. Im DPP müssen diese Stoffe angegeben werden, um sichere Handhabung, Recycling und informierte Kaufentscheidungen zu ermöglichen. |
| **GWP-Erklärung** | Erklärung zum Treibhauspotenzial (Global Warming Potential) — eine standardisierte Umweltkennzahl für Bauprodukte, die die Klimawirkung eines Produkts über seinen gesamten Lebenszyklus nach EN 15804 beziffert. |
| **EPD** | Umweltproduktdeklaration (Environmental Product Declaration) — ein standardisiertes Dokument (basierend auf ISO 14025 und EN 15804) zur Quantifizierung der Umweltauswirkungen eines Produkts über seinen Lebenszyklus. Für viele Bauprodukte Pflicht und Grundlage für DPP-Daten. |
| **BIM** | Building Information Modeling — ein digitaler Prozess zur Erstellung und Verwaltung von Gebäudeinformationen über den gesamten Lebenszyklus. Digitale Produktpässe für Bauprodukte sind auf die Integration mit BIM-Systemen ausgelegt. |
| **CEN/CLC/JTC 24** | Das gemeinsame europäische Normungsgremium, das für die Entwicklung der DPP-Standards verantwortlich ist. DPPA wirkt über Standard Norway an diesem Gremium mit. |
| **SN/K 624** | Norwegens nationales Spiegelkomitee für die Standardisierung Digitaler Produktpässe — bringt norwegische Expertise in die europäische DPP-Normung ein. DPPA ist Mitglied. |

## Was DPPA leistet

DPPA ermöglicht Herstellern, Importeuren, Händlern und Markeninhabern:

- **Digitale Produktpässe erstellen und veröffentlichen** — konform mit EU- und EWR-Vorschriften
- **QR- und NFC-Codes generieren** mit eingebetteten Produktdaten für Offline- und Online-Zugriff
- **Produktdaten verwalten** mit vollständiger Versionskontrolle, Prüfpfad und unveränderlicher Historie
- **Daten exportieren** im strukturierten JSON-Format — kein Vendor Lock-in
- **PIM- und ERP-Systeme anbinden** zur Synchronisierung und Automatisierung von Produktinformationen
- **Öffentlich zugängliche Produktabfragen bereitstellen** über einen leistungsstarken, global verteilten Webservice

## Branchen

DPPA bietet DPP-Lösungen für mehrere regulierte Produktkategorien:

- **Batterien** — EU-Batterieverordnung (2023/1542), verpflichtend ab 18. Februar 2027 für EV-Batterien, Industriebatterien >2 kWh und Leichtfahrzeug-Batterien
- **Textilien** — Delegierte Rechtsakte der ESPR voraussichtlich 2026–2027, verpflichtender DPP ab circa Mitte 2028 für Bekleidung, Schuhe und Heimtextilien
- **Bauprodukte** — Überarbeitete Bauproduktenverordnung mit GWP-Erklärungen ab Januar 2026 und DPP-Infrastruktur voraussichtlich ab 2027

## Plattform-Architektur

DPPA basiert auf **MACH-Architektur** (Modular, API-first, Cloud-native, Headless) und wird in **Microsoft Azure Rechenzentren in Europa** betrieben:

- **EU-basiertes Datenhosting** — Vollständige DSGVO-Konformität und EU-Datensouveränität
- **Enterprise-Grade-Sicherheit** — Azure Front Door, Web Application Firewall (WAF), verschlüsselte Speicherung, Zero-Trust-Sicherheitsmodell
- **Unveränderliche Versionierung** — Jede Produktveröffentlichung wird mit vollständiger Rückverfolgbarkeit gespeichert
- **Skalierbare Infrastruktur** — Ausgelegt auf Millionen von Produktpässen
- **Nutzungsbasierte Preise** — Pay-as-you-go, keine Lizenzgebühren, kein Vendor Lock-in

## Kernfunktionen

- **Excel-Import** — Massenupload von Produktdaten über strukturierte Vorlagen
- **PIM-/ERP-Integration** — Anbindung bestehender Produktinformationssysteme
- **Automatische QR-/NFC-Code-Erstellung** — Eindeutige digitale IDs für jedes Produkt
- **Öffentliche Produktabfrage** — Schneller, sicherer, leseoptimierter Webservice für Verbraucher und Partner
- **Unveränderliche Versionierung & Produkthistorie** — Lückenlose, prüfungssichere Rückverfolgbarkeit
- **JSON-Export** — Volle Datenportabilität für Archivierung, Integration oder Migration
- **Regulatorische Konformität** — Integrierte Unterstützung für DPP, ESPR, EU-Batterieverordnung und CPR

## Für wen ist DPPA?

| Zielgruppe | So hilft DPPA |
|------------|---------------|
| **Hersteller & Markeninhaber** | EU-DPP-Anforderungen erfüllen, QR-/NFC-Codes erstellen, Produktpässe im großen Maßstab veröffentlichen |
| **Compliance-Verantwortliche** | Zentralisierte, versionierte Daten, Prüfpfade, regulatorische Ausrichtung über EU und EWR |
| **Händler & Importeure** | Lieferanten-DPP-Konformität prüfen, Produktpässe hosten oder verlinken, Verbraucherzugang ermöglichen |
| **Entwickler & IT-Teams** | API-first MACH-Architektur, PIM-Integration, JSON-Export, modular und erweiterbar |

## Regulatorische Expertise & Standardisierung

DPPA erfüllt nicht nur DPP-Vorschriften — wir gestalten sie aktiv mit. Unser Team arbeitet direkt am Normungsprozess auf norwegischer und europäischer Ebene mit, was uns frühzeitigen Einblick in kommende Anforderungen gibt und die Möglichkeit, deren Ausgestaltung zu beeinflussen.

### Normungsgremien

- **Standard Norway (SN/K 624)** — Aktives Mitglied im norwegischen nationalen DPP-Normungskomitee; Mitwirkung an der Entwicklung norwegischer Positionen zu europäischen DPP-Standards
- **CEN/CLC/JTC 24** — Beteiligung an der europäischen DPP-Standardisierung über das gemeinsame CEN-CENELEC-Gremium, das die technischen Standards für die DPP-Umsetzung in der EU/im EWR entwickelt

### Regulatorisches Fachwissen

DPPA verfügt über fundiertes Wissen zum gesamten DPP-Rechtsrahmen:

- **[ESPR (Verordnung (EU) 2024/1781)](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)** — Die übergeordnete Ökodesign-Verordnung für nachhaltige Produkte
- **[EU-Batterieverordnung (2023/1542)](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng)** — Batteriepass-Anforderungen und Zeitpläne
- **Bauproduktenverordnung** — Überarbeitete CPR mit DPP-Bestimmungen
- **REACH und RoHS** — Offenlegungspflichten für besorgniserregende Stoffe
- **ISO/IEC 15459** — Standards für die eindeutige Produktidentifikation von Datenträgern
- **EN 15804** — Standards für Umweltproduktdeklarationen im Bauwesen
- **DIN DKE SPEC 99100** — Technische Spezifikation der Datenattribute für Batteriepässe

### Partner & Unterstützung

- **Innovation Norway** — Staatlich geförderte Finanzierung und Startup-Unterstützung
- **Microsoft AI Cloud Partner Program** — Azure-nativer Plattformpartner

## Early-Access-Partner

- **[Fair & Square](https://fairandsquare.no/)** — Norwegische Marke für ethische Textilien (Branchenpartner Textil)
- **[M.Door](https://mdoor.no/)** — Norwegischer Hersteller hochwertiger Innentüren (Branchenpartner Bauwesen)

## Compliance-Zeitplan

| Verordnung | Verpflichtender DPP ab | Status |
|------------|----------------------|--------|
| EU-Batterieverordnung (2023/1542) | 18. Februar 2027 | Gesetz — in Kraft |
| ESPR — Textilien | ca. Mitte 2028 (18 Monate nach delegiertem Rechtsakt) | Delegierter Rechtsakt wird 2026–2027 erwartet |
| Bauproduktenverordnung | 2027+ (schrittweise mit harmonisierten Standards) | GWP-Erklärungen seit Jan. 2026 erforderlich |

## Dokumentation

Ausführliche Dokumentation im Ordner [`docs-de/`](docs-de/):

### Plattform & Unternehmen
- [Funktionsübersicht](docs-de/funktionen.md)
- [Über DPPA](docs-de/ueber-uns.md)

### Für Ihre Rolle
- [Für Hersteller & Markeninhaber](docs-de/fuer-hersteller.md)
- [Für Compliance-Verantwortliche](docs-de/fuer-compliance.md)
- [Für Händler & Importeure](docs-de/fuer-haendler.md)
- [Für Entwickler & IT-Teams](docs-de/fuer-entwickler.md)

### Akademie — Branchenleitfäden
- [DPP für Batterien](docs-de/akademie/dpp-batterien.md)
- [DPP für Textilien](docs-de/akademie/dpp-textilien.md)
- [DPP für Bauprodukte](docs-de/akademie/dpp-bauprodukte.md)

### Akademie — Einblicke & Strategie
- [Was DPP 2026–2028 für Ihr Unternehmen bedeutet](docs-de/akademie/dpp-2026-bis-2028.md)
- [Praxisleitfaden zur DPP-Umsetzung vor 2027](docs-de/akademie/praktischer-leitfaden-vor-2027.md)
- [8 Geschäftsvorteile jenseits der Pflichterfüllung](docs-de/akademie/8-geschaeftsvorteile.md)
- [Von der DSGVO zum DPP: Was wir aus dem letzten Compliance-Sprint gelernt haben](docs-de/akademie/dsgvo-zu-dpp.md)

## Nachhaltigkeit als Grundprinzip

DPPA folgt dem Prinzip Sustainability by Design, angelehnt an das AWS Well-Architected Framework for Sustainability. Die Plattform nutzt verwaltete Azure-Services, um den Infrastruktur-Overhead zu minimieren, setzt Rechenressourcen bedarfsgerecht ein und verwendet Caching sowie Datendeduplizierung, um unnötige Verarbeitung zu vermeiden.

## Häufig gestellte Fragen

### Was ist ein Digitaler Produktpass und warum wird er vorgeschrieben?

Ein Digitaler Produktpass (DPP) ist ein strukturierter digitaler Datensatz, der mit einem physischen Produkt verknüpft ist und standardisierte Informationen über Zusammensetzung, Herkunft, Umweltauswirkungen, Konformitätsstatus und Entsorgung enthält. Die EU schreibt ihn im Rahmen der Ökodesign-Verordnung für nachhaltige Produkte (ESPR) vor, als Teil des European Green Deal für mehr Transparenz, Kreislaufwirtschaft und Nachhaltigkeit bei Produkten. Ziel ist es, Produktinformationen über den gesamten Lebenszyklus für Verbraucher, Behörden, Recycler und Lieferkettenpartner zugänglich zu machen.

### Ab wann sind Digitale Produktpässe Pflicht?

Die erste verbindliche Frist ist der **18. Februar 2027** für Batterien (EV-Batterien, Industriebatterien >2 kWh und Leichtfahrzeug-Batterien) gemäß EU-Verordnung 2023/1542. Für Textilien wird die Pflicht voraussichtlich ab **Mitte 2028** gelten, etwa 18 Monate nach Verabschiedung des entsprechenden delegierten Rechtsakts. Bei Bauprodukten ist der Zeitplan an harmonisierte Standards geknüpft, wobei GWP-Erklärungen für bestimmte Produkte bereits seit Januar 2026 vorgeschrieben sind. Weitere Produktkategorien werden sukzessive über delegierte Rechtsakte unter der ESPR hinzugefügt.

### Welche Produkte benötigen einen Digitalen Produktpass?

Die ESPR sieht DPP-Anforderungen für eine breite Palette von Produktkategorien vor. Die erste Welle umfasst Batterien, Textilien (Bekleidung, Schuhe, Heimtextilien) und Bauprodukte (Baumaterialien, Beschläge, Architekturelemente). Elektronik, Möbel, Chemikalien und weitere Produktgruppen sollen folgen. Jedes Produkt, das nach dem jeweiligen Stichtag auf dem EU-/EWR-Markt in Verkehr gebracht wird, muss einen gültigen DPP besitzen.

### Wer ist für die Erstellung eines Digitalen Produktpasses verantwortlich?

Gemäß der ESPR ist der **Wirtschaftsakteur** verantwortlich, der ein Produkt auf dem EU-/EWR-Markt in Verkehr bringt. Bei in der EU hergestellten Waren ist das in der Regel der Hersteller, bei Importware der Importeur. Auch Händler und Einzelhändler haben Prüfpflichten — sie müssen sicherstellen, dass die von ihnen vertriebenen Produkte über einen gültigen Pass verfügen.

### Welche Daten muss ein Digitaler Produktpass enthalten?

Die konkreten Anforderungen variieren je nach Produktkategorie (geregelt in delegierten Rechtsakten), aber die meisten DPPs müssen umfassen: Produktidentifikation (eindeutiger Identifikator nach ISO/IEC 15459), Herstellerangaben, Materialzusammensetzung, besorgniserregende Stoffe (REACH/RoHS), Umweltdaten (CO₂-Fußabdruck, Wasserverbrauch), Haltbarkeits- und Leistungsinformationen, Reparatur- und Demontageanleitungen, Recycling- und Entsorgungshinweise sowie Konformitätsnachweise. Alle Daten müssen maschinenlesbar und digital zugänglich sein.

### Wie greift man auf einen Digitalen Produktpass zu?

Jedes Produkt trägt einen **Datenträger** — in der Regel einen QR-Code oder NFC-Tag —, der auf seinen digitalen Pass verweist. Verbraucher, Behörden und Lieferkettenpartner können diesen Code scannen, um über einen webbasierten Service auf die Produktinformationen zuzugreifen. Grundlegende Daten können direkt im Datenträger für den Offline-Zugriff hinterlegt werden, während detaillierte Informationen online abrufbar sind. Es ist keine App-Installation erforderlich.

### Gilt die DPP-Pflicht auch außerhalb der EU?

Die DPP-Pflicht gilt für jedes Produkt, das **auf dem EU-/EWR-Markt in Verkehr gebracht wird** — unabhängig vom Herstellungsort. Wer in China, den USA oder anderswo produziert und in Europa verkauft, muss die Anforderungen erfüllen. Auch Norwegen, Island und Liechtenstein sind über das EWR-Abkommen einbezogen. China entwickelt vergleichbare Anforderungen mit Zieltermin 2027, und die USA prüfen digitale Kennzeichnungsstandards — der DPP dürfte zur globalen Norm werden.

### Was passiert, wenn ein Produkt keinen gültigen DPP hat?

Produkte ohne vorgeschriebenen DPP dürfen nicht auf dem EU-/EWR-Markt in Verkehr gebracht werden. Verstöße können zu Marktzugangsbeschränkungen, Bußgeldern und Reputationsschäden führen. Die Durchsetzung obliegt den Mitgliedstaaten, wobei die Sanktionsbestimmungen ab den jeweiligen Stichtagen greifen.

### Wie hängt ein DPP mit bestehenden Systemen wie PIM, ERP oder BIM zusammen?

Eine DPP-Plattform wie DPPA ergänzt bestehende Produktdatensysteme, statt sie zu ersetzen. Produktinformationen aus PIM- (Product Information Management), ERP- (Enterprise Resource Planning) oder PLM-Systemen (Product Lifecycle Management) lassen sich synchronisieren und auf die DPP-Datenstrukturen abbilden. Speziell bei Bauprodukten ist der DPP auf die Integration mit BIM-Systemen (Building Information Modeling) für das Lebenszyklusdatenmanagement ausgelegt.

### Was unterscheidet DPPA von anderen DPP-Lösungen?

DPPA ist von Grund auf für die DPP-Herausforderung konzipiert und bietet mehrere Alleinstellungsmerkmale: Wir wirken aktiv an der europäischen DPP-Standardisierung mit (SN/K 624, CEN/CLC/JTC 24) und haben so direkte Einblicke in kommende Anforderungen. Unsere Plattform basiert auf MACH-Architektur für Flexibilität und Herstellerunabhängigkeit, gehostet in EU-Azure-Rechenzentren für Datensouveränität. Wir bieten einen praxisnahen Einstieg (Start mit Excel, Skalierung auf API-Integration), besonders für KMU, die denselben Anforderungen wie Großunternehmen unterliegen, aber über weniger Ressourcen verfügen. Und wir garantieren volle Datenportabilität — Ihre Daten sind jederzeit als JSON exportierbar.

## Jetzt starten

1. **Gespräch vereinbaren** — Demo ansehen und Anforderungen besprechen
2. **Mit einem Produkt testen** — Kostenlos und unverbindlich
3. **Produktdaten übermitteln** — Per Excel-Vorlage oder PIM-Integration
4. **Prüfen, freigeben, live schalten** — Veröffentlichter DPP mit QR-/NFC-Codes und teilbaren Links

📧 [contact@dppa.no](mailto:contact@dppa.no)
🌐 [dppa.no](https://dppa.no)

---

*DPPA AS — Digitale Produktpässe für eine nachhaltige Zukunft. Entwickelt in Norwegen 🇳🇴*
