# Demo: průchod Velios intake konfigurátorem

## Scénář

**Firma:** ProvozPlus Servis s.r.o.  
**Segment:** SMB služby/provoz  
**Kontakt:** Jan Novák, jednatel  
**Zdroj:** Founder outbound  
**Cíl schůzky:** Ověřit úsporu času a prodat Fázi 0  

Velios firmu oslovil s hypotézou, že u nich existuje ruční předávání servisních zakázek mezi e-mailem, Excelem a účetním systémem.

## Krok 1: BANT kvalifikace

| Pole | Hodnota |
|---|---|
| Rozpočet | 300k-1M Kč |
| Target go-live | 30. 9. 2026 |
| Rozhodovatel | Ano, jednatel je na schůzce |
| Ekonomický buyer | Jan Novák, jednatel |
| Technický buyer | Externí IT správce |
| Champion | Vedoucí servisu |
| Blocker | Dodavatel účetního systému nemusí dodat API rychle |

## Krok 2: Dopad problému

Klient popsal problém:

> Servisní zakázky se přijímají e-mailem, ručně přepisují do Excelu a potom znovu do účetního systému. Vznikají chyby ve fakturaci a dispečink ztrácí přehled.

Výpočet dopadu:

| Metrika | Hodnota |
|---|---:|
| Lidé v procesu | 5 |
| Hodin týdně na osobu | 6 |
| Hodinový náklad | 650 Kč |
| Výjimky měsíčně | 18 |
| Náklad jedné výjimky | 1 200 Kč |
| Roční ztráta / náklad problému | 1 273 200 Kč |
| Potenciál měsíční úspory | 58 355 Kč |

## Krok 3: Rozhodovací strom

Potvrzené signály:

- Nahrazujeme Excel, e-maily, papír nebo ruční schvalování.
- Přepisují lidé data mezi systémy.
- Má se propojit účetnictví, ERP, CRM, sklad, e-shop nebo API.
- Má systém ukládat role, data, workflow nebo pravidla.

Vybrané oblasti:

- Interní systém
- Automatizace procesů
- API / účetní integrace
- Backend / databáze

## Krok 4: Dynamická diagnostika

| Oblast | Zjištění |
|---|---|
| Interní systém | 5 interních uživatelů: dispečink, vedoucí servisu, účetní. Nahrazuje Excel tabulku servisních zakázek a e-mailové předávání. |
| Automatizace | Proces: přijetí zakázky, kontrola údajů, předání technikovi, podklad pro fakturaci. Bere cca 30 hodin týdně. |
| Integrace | Účetní systém Pohoda a sdílený Excel/Outlook. API dokumentace zatím není potvrzená. |
| Backend | Zatím není vlastní systém, pouze Microsoft 365 a účetní systém. Cca 250 servisních zakázek měsíčně. |

## Krok 5: Výsledek konfigurátoru

| Výstup | Hodnota |
|---|---|
| Deal score | 78/100 |
| VELYOS fit | Diagnostika nutná |
| ICP fit | Vysoký ICP fit, 5/5 |
| Outbound segment | SMB provoz |
| Doporučený obchodní asset | Fáze 0 one-pager + procesní ROI kalkulace |
| Case study potenciál | Vhodné pro case study |
| Doporučený další krok | Placená diagnostika |

Doporučený další krok:

> Velios Fáze 0: Procesní a technická diagnostika: 15-30k Kč, 3-7 pracovních dnů. Před cenou ověřit proces, data, integrace, rizika a business case.

## Role matrix

Zapojit:

- PM
- Analyst
- Backend
- QA
- DevOps

Nezapojovat:

- UX/UI
- Frontend
- Security
- AI/Data
- Mobile
- Tech Lead

## Rizika

- Identifikovaný blocker v nákupním nebo technickém rozhodování.
- Integrační projekt bez potvrzené API dokumentace.

## CRM zápis ve zkrácené podobě

```text
Firma: ProvozPlus Servis s.r.o.
Kontakt: Jan Novák, jednatel
Zdroj: Founder outbound
Segment: SMB služby/provoz
Primární nabídka: Automatizace a digitalizace procesů
GTM motion: Founder outbound
ICP fit: Vysoký ICP fit (5/5)
Outbound segment: SMB provoz
Doporučený obchodní asset: Fáze 0 one-pager + procesní ROI kalkulace
Case study potenciál: Vhodné pro case study
Rozpočet: 300k-1M Kč
Target go-live: 30. 9. 2026
Rozhodovatel: Ano
Vybrané oblasti: Interní systém, automatizace, integrace, backend
Roční ztráta / náklad problému: 1 273 200 Kč
Potenciál měsíční úspory: 58 355 Kč
Doporučený další krok: Placená diagnostika
```

## Follow-up e-mail klientovi

```text
Předmět: Velios - shrnutí a navržený další krok pro ProvozPlus Servis s.r.o.

Dobrý den,

děkuji za dnešní rozhovor. Stručně shrnuji, co jsme si odnesli:

- řešené oblasti: interní systém, automatizace procesů, účetní integrace a backend
- hlavní popsaný problém: servisní zakázky se přijímají e-mailem, ručně přepisují do Excelu a potom znovu do účetního systému
- orientační roční náklad současného stavu: 1 273 200 Kč
- doporučený další krok: placená diagnostika
- primární zaměření Velios: automatizace a digitalizace procesů

Navrhujeme nepřipravovat závaznou cenu bez ověření rozsahu. Další smysluplný krok je Velios Fáze 0: Procesní a technická diagnostika za 15-30k Kč v délce 3-7 pracovních dnů.

Ve Fázi 0 ověříme proces, technické vstupy, rizika a doporučíme nejkratší cestu k měřitelnému výsledku.

Výstupem bude mapa procesu, odhad úspory času, rizika, role, technické vstupy, scope fáze 1 a doporučení nabídka / stop.

S pozdravem
Velios
```
