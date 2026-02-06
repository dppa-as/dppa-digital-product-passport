# DPPA — Platforma cyfrowego paszportu produktu

*[🇬🇧 English](README.md) | [🇳🇴 Norsk](README.nb.md) | [🇩🇪 Deutsch](README.de.md) | 🇵🇱 Polski | [🇸🇰 Slovenčina](README.sk.md)*

**DPPA AS** to norweska platforma SaaS do tworzenia, zarządzania i wydawania **cyfrowych paszportów produktów (DPP)** — zgodnie z przepisami UE, w tym **Rozporządzeniem w sprawie ekoprojektu dla zrównoważonych produktów (ESPR)**, **Rozporządzeniem UE w sprawie baterii** oraz **Rozporządzeniem w sprawie wyrobów budowlanych (CPR)**.

🌐 Strona: [dppa.no](https://dppa.no)
📧 Kontakt: [contact@dppa.no](mailto:contact@dppa.no)
🏢 Nr org.: 935 969 425 (Sandefjord, Norwegia)

---

## Czym jest cyfrowy paszport produktu?

Cyfrowy paszport produktu (Digital Product Passport, DPP) to ustrukturyzowany cyfrowy zapis powiązany z produktem fizycznym — dostępny przez kod QR lub NFC. Zawiera znormalizowane informacje o materiałach, pochodzeniu, wskaźnikach zrównoważonego rozwoju, dokumentacji zgodności oraz instrukcjach dotyczących końca cyklu życia. DPP jest kluczowym narzędziem Europejskiego Zielonego Ładu i Rozporządzenia w sprawie ekoprojektu dla zrównoważonych produktów (ESPR).

## Kluczowe pojęcia

| Termin | Definicja |
|--------|-----------|
| **Cyfrowy paszport produktu (DPP)** | Ustrukturyzowany, maszynowo odczytywalny cyfrowy zapis powiązany z produktem fizycznym przez kod QR lub NFC. Zawiera znormalizowane dane o materiałach, pochodzeniu, śladzie węglowym, statusie zgodności i instrukcjach utylizacji. Wymagany prawnie dla coraz większej liczby kategorii produktów. |
| **ESPR** | Rozporządzenie w sprawie ekoprojektu dla zrównoważonych produktów ([Rozporządzenie (UE) 2024/1781](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)) — nadrzędne ramy UE dotyczące cyfrowych paszportów produktów, wymagań efektywności i kryteriów zrównoważonego rozwoju dla produktów sprzedawanych na rynku UE/EOG. Weszło w życie 18 lipca 2024. |
| **Rozporządzenie UE w sprawie baterii** | [Rozporządzenie (UE) 2023/1542](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng) — wymaga paszportów baterii dla baterii EV, baterii przemysłowych >2 kWh i baterii lekkich środków transportu od 18 lutego 2027. Pierwsza kategoria produktów z obowiązkowym terminem DPP. |
| **Rozporządzenie w sprawie wyrobów budowlanych (CPR)** | Znowelizowane CPR reguluje wyroby budowlane na rynku UE/EOG. Wprowadza wymogi cyfrowego paszportu produktu obok istniejącego oznakowania CE, z deklaracjami GWP (potencjał globalnego ocieplenia) wymaganymi od stycznia 2026 dla niektórych produktów. |
| **Akt delegowany** | Prawo wtórne przyjmowane przez Komisję Europejską, określające szczegółowe wymagania DPP dla każdej kategorii produktów — w tym wymagane pola danych, nośniki danych, poziomy dostępu i terminy. Każda grupa produktów otrzymuje własny akt delegowany w ramach ESPR. |
| **Nośnik danych** | Fizyczny mechanizm (kod QR, tag NFC, chip RFID lub Data Matrix) umieszczony na produkcie, który odsyła do jego cyfrowego paszportu produktu. Musi spełniać normę ISO/IEC 15459 dla jednoznacznej identyfikacji. |
| **Architektura MACH** | Modular, API-first, Cloud-native, Headless — nowoczesny wzorzec architektury oprogramowania umożliwiający elastyczną integrację, niezależne skalowanie i wdrożenia niezależne od dostawcy. Platforma DPPA jest zbudowana na zasadach MACH. |
| **Podmiot gospodarczy** | Każdy producent, importer, dystrybutor, upoważniony przedstawiciel lub dostawca usług fulfillment zaangażowany we wprowadzanie produktu na rynek UE/EOG. Zgodnie z ESPR podmiot gospodarczy odpowiedzialny za wprowadzenie produktu na rynek musi zapewnić istnienie ważnego DPP. |
| **Substancje potencjalnie niebezpieczne** | Chemikalia w produktach mogące stanowić zagrożenie dla zdrowia ludzkiego lub środowiska, regulowane przez REACH i RoHS. W DPP musi być ujawniona obecność tych substancji, aby umożliwić bezpieczne obchodzenie się z produktem, recykling i świadome decyzje zakupowe. |
| **Deklaracja GWP** | Deklaracja potencjału globalnego ocieplenia (Global Warming Potential) — znormalizowany wskaźnik środowiskowy wymagany dla wyrobów budowlanych, mierzący wpływ produktu na klimat w całym cyklu życia na podstawie norm EN 15804. |
| **EPD** | Deklaracja środowiskowa produktu (Environmental Product Declaration) — znormalizowany dokument (oparty na ISO 14025 i EN 15804) określający ilościowo wpływ produktu na środowisko w całym cyklu życia. Wymagany dla wielu wyrobów budowlanych i stanowiący podstawę danych DPP. |
| **BIM** | Building Information Modeling — cyfrowy proces tworzenia i zarządzania informacjami o budynku przez cały jego cykl życia. Cyfrowe paszporty produktów dla wyrobów budowlanych są zaprojektowane z myślą o integracji z systemami BIM. |
| **CEN/CLC/JTC 24** | Wspólny europejski komitet techniczny ds. normalizacji odpowiedzialny za opracowywanie standardów DPP. DPPA uczestniczy w pracach tego komitetu poprzez Standard Norway. |
| **SN/K 624** | Norweski krajowy komitet lustrzany ds. normalizacji cyfrowego paszportu produktu — wnoszący norweską wiedzę ekspercką do europejskich prac normalizacyjnych DPP. DPPA jest członkiem. |

## Co oferuje DPPA

DPPA umożliwia producentom, importerom, sprzedawcom i właścicielom marek:

- **Tworzenie i publikowanie cyfrowych paszportów produktów** — zgodnych z przepisami UE i EOG
- **Generowanie kodów QR i NFC** z osadzonymi danymi produktowymi dla dostępu offline i online
- **Zarządzanie danymi produktowymi** z pełną kontrolą wersji, ścieżką audytu i niezmienną historią
- **Eksportowanie danych** w ustrukturyzowanym formacie JSON — bez uzależnienia od dostawcy
- **Integrację z systemami PIM i ERP** w celu synchronizacji i automatyzacji informacji o produktach
- **Udostępnianie publicznie dostępnych wyszukiwarek produktów** poprzez wydajny, globalnie dystrybuowany serwis webowy

## Branże

DPPA dostarcza rozwiązania DPP dla wielu regulowanych kategorii produktów:

- **Baterie** — Rozporządzenie UE w sprawie baterii (2023/1542), obowiązkowe od 18 lutego 2027 dla baterii EV, baterii przemysłowych >2 kWh i baterii lekkich środków transportu
- **Tekstylia** — Akty delegowane ESPR przewidywane na 2026–2027, obowiązkowy DPP od około połowy 2028 dla odzieży, obuwia i tekstyliów domowych
- **Wyroby budowlane** — Znowelizowane Rozporządzenie w sprawie wyrobów budowlanych z deklaracjami GWP od stycznia 2026 i infrastrukturą DPP przewidywaną od 2027

## Architektura platformy

DPPA jest zbudowana na **architekturze MACH** (Modular, API-first, Cloud-native, Headless) i hostowana w **europejskich centrach danych Microsoft Azure**:

- **Hosting danych w UE** — Pełna zgodność z RODO i suwerenność danych UE
- **Bezpieczeństwo klasy enterprise** — Azure Front Door, Web Application Firewall (WAF), szyfrowane przechowywanie, model bezpieczeństwa zero-trust
- **Niezmienna wersjonowanie** — Każda publikacja produktu jest zapisywana z pełną identyfikowalnością
- **Skalowalna infrastruktura** — Zaprojektowana do obsługi milionów paszportów produktów
- **Ceny oparte na zużyciu** — Pay-as-you-go, bez opłat licencyjnych, bez uzależnienia od dostawcy

## Kluczowe funkcje

- **Import z Excela** — Masowe przesyłanie danych produktowych za pomocą ustrukturyzowanych szablonów
- **Integracja PIM/ERP** — Podłączenie istniejących systemów informacji o produktach
- **Automatyczne generowanie kodów QR/NFC** — Unikalne cyfrowe identyfikatory dla każdego produktu
- **Publiczne wyszukiwanie produktów** — Szybki, bezpieczny, zoptymalizowany pod kątem odczytu serwis webowy dla konsumentów i partnerów
- **Niezmienna wersjonowanie i historia produktu** — Pełna, gotowa do audytu identyfikowalność
- **Eksport JSON** — Pełna przenośność danych do archiwizacji, integracji lub migracji
- **Zgodność regulacyjna** — Wbudowane wsparcie dla DPP, ESPR, Rozporządzenia w sprawie baterii i CPR

## Dla kogo jest DPPA?

| Grupa docelowa | Jak pomaga DPPA |
|----------------|-----------------|
| **Producenci i właściciele marek** | Spełnianie wymogów UE dotyczących DPP, generowanie kodów QR/NFC, publikowanie paszportów produktów na dużą skalę |
| **Specjaliści ds. zgodności** | Scentralizowane, wersjonowane dane, ścieżki audytu, zgodność regulacyjna w UE i EOG |
| **Sprzedawcy i importerzy** | Weryfikacja zgodności DPP dostawców, hosting lub linkowanie do paszportów produktów, umożliwienie dostępu konsumentom |
| **Deweloperzy i zespoły IT** | Architektura MACH zorientowana na API, integracja PIM, eksport JSON, modułowość i rozszerzalność |

## Ekspertyza regulacyjna i normalizacja

DPPA nie tylko spełnia przepisy dotyczące DPP — aktywnie je współtworzy. Nasz zespół jest bezpośrednio zaangażowany w proces tworzenia standardów na poziomie norweskim i europejskim, co daje nam wczesny wgląd w nadchodzące wymagania i możliwość wpływania na ich kształt.

### Organy normalizacyjne

- **Standard Norway (SN/K 624)** — Aktywny członek norweskiego krajowego komitetu normalizacyjnego ds. DPP, współtworzący norweskie stanowiska wobec europejskich standardów DPP
- **CEN/CLC/JTC 24** — Zaangażowanie w europejską normalizację DPP poprzez wspólny komitet techniczny CEN-CENELEC, który opracowuje standardy techniczne będące podstawą wdrożenia DPP w UE/EOG

### Wiedza regulacyjna

DPPA dysponuje głęboką wiedzą o całym systemie regulacyjnym DPP:

- **[ESPR (Rozporządzenie (UE) 2024/1781)](https://eur-lex.europa.eu/eli/reg/2024/1781/oj)** — Nadrzędne Rozporządzenie w sprawie ekoprojektu dla zrównoważonych produktów
- **[Rozporządzenie UE w sprawie baterii (2023/1542)](https://eur-lex.europa.eu/eli/reg/2023/1542/oj/eng)** — Wymogi i terminy dotyczące paszportu baterii
- **Rozporządzenie w sprawie wyrobów budowlanych** — Znowelizowane CPR z przepisami dotyczącymi cyfrowego paszportu produktu
- **REACH i RoHS** — Wymogi ujawniania substancji potencjalnie niebezpiecznych
- **ISO/IEC 15459** — Standardy jednoznacznej identyfikacji produktów dla nośników danych
- **EN 15804** — Standardy deklaracji środowiskowych produktów dla budownictwa
- **DIN DKE SPEC 99100** — Specyfikacja techniczna atrybutów danych paszportu baterii

### Partnerstwa i wsparcie

- **Innovation Norway** — Finansowanie i wsparcie startupów przez norweski rząd
- **Microsoft AI Cloud Partner Program** — Partner platformy natywnej Azure

## Partnerzy Early-Access

- **[Fair & Square](https://fairandsquare.no/)** — Norweska marka etycznych tekstyliów (partner branży tekstylnej)
- **[M.Door](https://mdoor.no/)** — Norweski producent wysokiej jakości drzwi wewnętrznych (partner branży budowlanej)

## Harmonogram zgodności

| Rozporządzenie | Obowiązkowy DPP od | Status |
|----------------|-------------------|--------|
| Rozporządzenie UE w sprawie baterii (2023/1542) | 18 lutego 2027 | Prawo — obowiązuje |
| ESPR — Tekstylia | ~połowa 2028 (18 miesięcy po akcie delegowanym) | Akt delegowany oczekiwany 2026–2027 |
| Rozporządzenie w sprawie wyrobów budowlanych | 2027+ (etapowo wraz z harmonizowanymi standardami) | Deklaracje GWP wymagane od sty. 2026 |

## Dokumentacja

Szczegółowa dokumentacja w folderze [`docs-pl/`](docs-pl/):

### Platforma i firma
- [Przegląd funkcji](docs-pl/funkcje.md)
- [O DPPA](docs-pl/o-nas.md)

### Dla Twojej roli
- [Dla producentów i właścicieli marek](docs-pl/dla-producentow.md)
- [Dla specjalistów ds. zgodności](docs-pl/dla-compliance.md)
- [Dla sprzedawców i importerów](docs-pl/dla-sprzedawcow.md)
- [Dla deweloperów i zespołów IT](docs-pl/dla-deweloperow.md)

### Akademia — Przewodniki branżowe
- [DPP dla baterii](docs-pl/akademia/dpp-baterie.md)
- [DPP dla tekstyliów](docs-pl/akademia/dpp-tekstylia.md)
- [DPP dla wyrobów budowlanych](docs-pl/akademia/dpp-budownictwo.md)

### Akademia — Analizy i strategia
- [Co DPP oznacza dla Twojej firmy w latach 2026–2028](docs-pl/akademia/dpp-2026-do-2028.md)
- [Praktyczny przewodnik wdrożenia DPP przed 2027](docs-pl/akademia/praktyczny-przewodnik-przed-2027.md)
- [8 korzyści biznesowych wykraczających poza zgodność regulacyjną](docs-pl/akademia/8-korzysci-biznesowych.md)
- [Od RODO do DPP: Czego nauczył nas ostatni sprint zgodności](docs-pl/akademia/rodo-do-dpp.md)

## Zbudowane z myślą o zrównoważonym rozwoju

DPPA stosuje zasady sustainability-by-design zainspirowane AWS Well-Architected Framework for Sustainability. Platforma wykorzystuje zarządzane usługi Azure, aby minimalizować obciążenie infrastrukturalne, dopasowuje zasoby obliczeniowe do rzeczywistych potrzeb, aby unikać marnowania energii, oraz stosuje efektywne cachowanie i deduplikację danych w celu ograniczenia zbędnego przetwarzania.

## Najczęściej zadawane pytania

### Czym jest cyfrowy paszport produktu i dlaczego jest wymagany?

Cyfrowy paszport produktu (DPP) to ustrukturyzowany cyfrowy zapis powiązany z produktem fizycznym, zawierający znormalizowane informacje o jego składzie, pochodzeniu, wpływie na środowisko, statusie zgodności i sposobie utylizacji. Jest wymagany na mocy unijnego Rozporządzenia w sprawie ekoprojektu dla zrównoważonych produktów (ESPR) jako część dążeń Europejskiego Zielonego Ładu do przejrzystości, cyrkularności i zrównoważonego rozwoju produktów. Celem jest udostępnienie informacji o produkcie konsumentom, regulatorom, recyklerom i partnerom w łańcuchu dostaw przez cały cykl życia produktu.

### Kiedy cyfrowe paszporty produktów stają się obowiązkowe?

Pierwszy obowiązkowy termin to **18 lutego 2027** dla baterii (baterie EV, baterie przemysłowe >2 kWh i baterie lekkich środków transportu) zgodnie z Rozporządzeniem UE 2023/1542. Tekstylia mają być objęte obowiązkiem około **połowy 2028**, czyli około 18 miesięcy po przyjęciu odpowiedniego aktu delegowanego przez Komisję Europejską. Wyroby budowlane będą objęte stopniowym harmonogramem powiązanym z aktualizacjami harmonizowanych standardów, przy czym deklaracje GWP są już wymagane dla niektórych produktów od stycznia 2026. Dodatkowe kategorie produktów będą dodawane stopniowo poprzez akty delegowane w ramach ESPR.

### Które produkty potrzebują cyfrowego paszportu produktu?

ESPR ustanawia wymogi DPP dla szerokiego zakresu kategorii produktów. Pierwsza fala obejmuje baterie, tekstylia (odzież, obuwie, tekstylia domowe) i wyroby budowlane (materiały budowlane, okucia, elementy architektoniczne). UE zasygnalizowała, że elektronika, meble, chemikalia i inne grupy produktów będą następne. Każdy produkt wprowadzony na rynek UE/EOG po odpowiedniej dacie obowiązkowej musi posiadać ważny DPP.

### Kto jest odpowiedzialny za utworzenie cyfrowego paszportu produktu?

Zgodnie z ESPR za zapewnienie istnienia ważnego DPP odpowiada **podmiot gospodarczy**, który wprowadza produkt na rynek UE/EOG. W przypadku towarów produkowanych w UE jest to zazwyczaj producent, a w przypadku towarów wytwarzanych poza UE — importer. Dystrybutorzy i sprzedawcy detaliczni również mają obowiązki weryfikacyjne — muszą upewnić się, że sprzedawane przez nich produkty posiadają ważne paszporty.

### Jakie dane musi zawierać cyfrowy paszport produktu?

Choć szczegółowe wymagania różnią się w zależności od kategorii produktu (określone w aktach delegowanych), większość DPP musi zawierać: identyfikację produktu (unikalny identyfikator zgodny z ISO/IEC 15459), dane producenta, skład materiałowy, substancje potencjalnie niebezpieczne (REACH/RoHS), dane środowiskowe (ślad węglowy, zużycie wody), informacje o trwałości i wydajności, instrukcje naprawy i demontażu, wskazówki dotyczące recyklingu i utylizacji oraz dokumentację zgodności. Wszystkie dane muszą być maszynowo odczytywalne i dostępne cyfrowo.

### Jak uzyskuje się dostęp do cyfrowego paszportu produktu?

Każdy produkt posiada **nośnik danych** — zazwyczaj kod QR lub tag NFC — który odsyła do jego cyfrowego paszportu. Konsumenci, regulatorzy i partnerzy w łańcuchu dostaw mogą zeskanować ten kod, aby uzyskać dostęp do informacji o produkcie za pośrednictwem serwisu webowego. Podstawowe dane mogą być osadzone bezpośrednio w nośniku danych dla dostępu offline, podczas gdy szczegółowe informacje są hostowane online. Nie jest wymagana instalacja żadnej aplikacji.

### Czy wymóg DPP obowiązuje poza UE?

Wymóg DPP dotyczy każdego produktu **wprowadzanego na rynek UE/EOG**, niezależnie od miejsca jego wytworzenia. Jeśli produkujesz w Chinach, USA lub gdziekolwiek indziej i sprzedajesz do Europy, musisz spełnić wymagania. Dodatkowo Norwegia, Islandia i Liechtenstein są objęte umową o EOG. Chiny rozwijają podobne wymagania z celem na 2027, a USA bada standardy cyfrowego etykietowania — co sugeruje, że DPP stanie się globalną normą.

### Co się stanie, jeśli produkt nie ma ważnego DPP?

Produkty bez wymaganego DPP nie mogą być legalnie wprowadzone na rynek UE/EOG. Niezgodność może skutkować ograniczeniami dostępu do rynku, karami finansowymi i utratą reputacji. Za egzekwowanie odpowiadają państwa członkowskie, a przepisy dotyczące kar obowiązują od odpowiednich dat obowiązkowych.

### Jak DPP ma się do istniejących systemów takich jak PIM, ERP czy BIM?

Platforma DPP taka jak DPPA integruje się z istniejącymi systemami danych produktowych, zamiast je zastępować. Informacje o produktach z systemów PIM (Product Information Management), ERP (Enterprise Resource Planning) lub PLM (Product Lifecycle Management) mogą być synchronizowane i mapowane na struktury danych wymagane przez DPP. Szczególnie w przypadku wyrobów budowlanych DPP są zaprojektowane z myślą o integracji z systemami BIM (Building Information Modeling) do zarządzania danymi cyklu życia.

### Czym DPPA różni się od innych rozwiązań DPP?

DPPA jest od podstaw zaprojektowana do wyzwań związanych z DPP i oferuje kilka wyróżników: aktywnie uczestniczymy w europejskiej normalizacji DPP (SN/K 624, CEN/CLC/JTC 24), co daje nam bezpośredni wgląd w nadchodzące wymagania. Nasza platforma jest zbudowana na architekturze MACH zapewniającej elastyczność i brak uzależnienia od dostawcy, hostowana w europejskich centrach danych Azure dla suwerenności danych. Oferujemy praktyczną ścieżkę wdrożenia (start z Excelem, skalowanie do integracji API) zaprojektowaną specjalnie dla MŚP, które stoją przed tymi samymi wymaganiami co duże przedsiębiorstwa, ale dysponują mniejszymi zasobami. I zapewniamy pełną przenośność danych — Twoje dane są zawsze eksportowalne w formacie JSON.

## Jak zacząć

1. **Umów rozmowę** — Obejrzyj demo i omów swoje potrzeby
2. **Wypróbuj z jednym produktem** — Bez kosztów, bez ryzyka
3. **Prześlij dane produktowe** — Przez szablon Excel lub integrację PIM
4. **Przejrzyj, zatwierdź i uruchom** — Opublikowany DPP z kodami QR/NFC i linkami do udostępniania

📧 [contact@dppa.no](mailto:contact@dppa.no)
🌐 [dppa.no](https://dppa.no)

---

*DPPA AS — Cyfrowe paszporty produktów dla zrównoważonej przyszłości. Stworzone w Norwegii 🇳🇴*
