# Cyfrowy paszport produktu dla deweloperów i zespołów IT

*[🇬🇧 English](../docs/for-developers.md) | [🇳🇴 Norsk](../docs-nb/for-utviklere.md) | [🇩🇪 Deutsch](../docs-de/fuer-entwickler.md) | 🇵🇱 Polski | [🇸🇰 Slovenčina](../docs-sk/pre-vyvojarov.md)*

> Napędzanie cyfrowych paszportów produktów skalowalną, przyszłościową technologią

🌐 [dppa.no/for-developers](https://dppa.no/for-developers/)

---

## Co DPP oznacza dla deweloperów i zespołów technicznych

Cyfrowe paszporty produktów fundamentalnie zmieniają zarządzanie danymi produktowymi i zgodność regulacyjną. Jako deweloper, architekt IT lub CTO, masz za zadanie integrować różnorodne źródła danych, umożliwiać bezpieczną wymianę danych i zapewniać płynny publiczny i wewnętrzny dostęp — jednocześnie utrzymując systemy skalowalne i łatwe w utrzymaniu.

Mandat DPP wprowadza nową złożoność: ewoluujące standardy, wyzwania interoperacyjności oraz wymóg danych w czasie rzeczywistym, weryfikowalnych w rozproszonych łańcuchach dostaw.

## Wyzwania techniczne

- **Fragmentacja i heterogeniczność danych** — Wiele źródeł danych produktowych, formatów i standardów
- **Ewoluujące przepisy** — Ciągłe aktualizacje wymagające adaptacyjnych implementacji
- **Wymagania wydajności i bezpieczeństwa** — Publiczny dostęp do danych produktowych musi być szybki, niezawodny i bezpieczny globalnie
- **Unikanie uzależnienia od dostawcy** — Rozwiązania muszą umożliwiać elastyczność przy migracji, audycie i przenośności danych
- **Łączenie świata technicznego z biznesowym** — Tłumaczenie wymagań technicznych dla zespołów compliance i biznesu

## Jak pomaga DPPA

### Elastyczne modelowanie danych i relacje

Hierarchiczne relacje produktowe — rodzice, dzieci i substytuty sibling — nawet między różnymi dostawcami DPP. Relacje linkowane przez URLe, bez duplikowania danych.

### Łatwe wdrażanie danych i mapowanie

Upload arkuszy kalkulacyjnych lub podłączenie systemów PIM dla płynnego mapowania atrybutów i synchronizacji.

### Modułowa platforma API-First

Zbudowana na architekturze MACH — API-first, natywna dla chmury i rozszerzalna. Łatwa integracja i przyszłościowa skalowalność.

### Zoptymalizowana warstwa dostępu publicznego

Podstawowe dane produktowe osadzone offline w kodach QR/NFC, w połączeniu z globalnie dystrybuowanym, wydajnym publicznym serwisem webowym.

### Solidne wersjonowanie i eksportowalność

Wszystkie dane wersjonowane, eksportowalne i przenośne w formacie JSON. Pełna kontrola bez uzależnienia od dostawcy.

## Szczegóły techniczne platformy

- **Architektura:** MACH (Modular, API-first, Cloud-native, Headless)
- **Dostawca chmury:** Microsoft Azure (centra danych w UE)
- **Bezpieczeństwo:** Azure Front Door, WAF, szyfrowane przechowywanie, model zero-trust
- **Format danych:** Ustrukturyzowany eksport JSON
- **Integracje:** Systemy PIM (Akeneo, PimCore, inRiver), import Excel
- **W planach:** REST API do wydawania, aktualizacji i walidacji paszportów; SDK i środowiska sandbox

## FAQ

**Jakie API obecnie wspieracie?**
Import Excel i integracja PIM z wsparciem mapowania atrybutów. Pełne REST API planowane w przyszłym wydaniu.

**Jak radzicie sobie ze skalowalnością?**
Natywne dla chmury na Azure, skalowanie do milionów SKU i wysokiego ruchu globalnie bez opóźnień.

**A co z własnością danych?**
Zachowujesz pełną własność. Wszystkie dane eksportowalne w JSON — bez uzależnienia od dostawcy.

**Standardy bezpieczeństwa?**
Centra danych w UE, model zero-trust, zgodność z RODO, trwające prace nad certyfikacją ISO i SOC.

---

📧 [contact@dppa.no](mailto:contact@dppa.no) | 🌐 [dppa.no](https://dppa.no)
