# Digitálny pas produktu pre vývojárov a IT tímy

*[🇬🇧 English](../docs/for-developers.md) | [🇳🇴 Norsk](../docs-nb/for-utviklere.md) | [🇩🇪 Deutsch](../docs-de/fuer-entwickler.md) | [🇵🇱 Polski](../docs-pl/dla-deweloperow.md) | 🇸🇰 Slovenčina*

> Digitálne pasy produktov poháňané škálovateľnou technológiou pripravenou na budúcnosť

🌐 [dppa.no/for-developers](https://dppa.no/for-developers/)

---

## Čo DPP znamená pre vývojárov a technické tímy

Digitálne pasy produktov zásadne menia správu produktových dát a regulačný súlad. Ako vývojár, IT architekt alebo CTO máte za úlohu integrovať rozmanité zdroje dát, umožniť bezpečnú výmenu dát a zabezpečiť plynulý verejný aj interný prístup, a zároveň udržiavať systémy škálovateľné a ľahko spravovateľné.

Mandát DPP prináša novú komplexitu: vyvíjajúce sa štandardy, výzvy v oblasti interoperability a požiadavku na dáta v reálnom čase, overiteľné naprieč distribuovanými dodávateľskými reťazcami.

## Technické výzvy

- **Roztrieštené a heterogénne dáta:** Množstvo zdrojov produktových dát, formátov a štandardov
- **Vyvíjajúce sa predpisy:** Neustále zmeny vyžadujúce prispôsobiteľné implementácie
- **Nároky na výkon a bezpečnosť:** Verejný prístup k produktovým dátam musí byť rýchly, spoľahlivý a bezpečný v globálnom meradle
- **Vyhnutie sa závislosti od dodávateľa:** Riešenia musia umožňovať flexibilitu pri migrácii, auditoch a prenositeľnosti dát
- **Prepojenie technického a biznesového sveta:** Prekladanie technických požiadaviek pre compliance a obchodné tímy

## Ako pomáha DPPA

### Flexibilné modelovanie dát a vzťahov

Hierarchické vzťahy medzi produktmi (rodič, dieťa a súrodenecké náhrady), a to aj medzi rôznymi poskytovateľmi DPP. Vzťahy prepojené cez URL adresy bez duplikovania dát.

### Jednoduché zavedenie dát a mapovanie

Nahrajte tabuľky alebo pripojte PIM systémy na plynulé mapovanie atribútov a synchronizáciu.

### Modulárna platforma s prístupom API-first

Postavená na architektúre MACH: API-first, cloud-natívna a rozšíriteľná. Jednoduchá integrácia a škálovateľnosť pripravená na budúcnosť.

### Optimalizovaná vrstva verejného prístupu

Základné produktové dáta zabudované offline v QR/NFC kódoch, doplnené globálne distribuovanou výkonnou verejnou webovou službou.

### Robustné verzionovanie a exportovateľnosť

Všetky dáta verzionované, exportovateľné a prenosné vo formáte JSON. Plná kontrola bez závislosti od dodávateľa.

## Technické detaily platformy

- **Architektúra:** MACH (Modular, API-first, Cloud-native, Headless)
- **Cloudový poskytovateľ:** Microsoft Azure (dátové centrá v EÚ)
- **Bezpečnosť:** Azure Front Door, WAF, šifrované úložisko, model zero-trust
- **Formát dát:** Štruktúrovaný export JSON
- **Integrácie:** PIM systémy (Akeneo, PimCore, inRiver), import z Excelu
- **Pripravujeme:** REST API na vydávanie, aktualizáciu a validáciu pasov; SDK a sandbox prostredia

## FAQ

**Aké API v súčasnosti podporujete?**
Import z Excelu a integráciu PIM so sprevádza­ným mapovaním atribútov. Plné REST API je plánované v budúcom vydaní.

**Ako riešite škálovateľnosť?**
Cloud-natívne riešenie na Azure, škálovateľné na milióny SKU a vysokú prevádzku globálne bez latencie.

**Ako je to s vlastníctvom dát?**
Zachovávate si plné vlastníctvo. Všetky dáta sú exportovateľné vo formáte JSON, žiadna závislosť od dodávateľa.

**Bezpečnostné štandardy?**
Dátové centrá v EÚ, model zero-trust, súlad s GDPR, prebiehajúce úsilie o certifikáciu ISO a SOC.

---

📧 [contact@dppa.no](mailto:contact@dppa.no) | 🌐 [dppa.no](https://dppa.no)
