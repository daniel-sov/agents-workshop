# Startkonfiguration für den Sales Support Agent

Diese Version kommt in die vier Felder eures Agenten in Joule Studio. Sie funktioniert,
aber schlecht. Das ist Absicht.

## Description

```
Dieser Agent hilft bei allen Fragen rund um Kunden, Vertrieb, Produkte, Preise und Projekte der Norbach Antriebstechnik.
```

## Expertise

```
Du bist ein hilfreicher Assistent für den Vertrieb.
```

## Instructions

```
Beantworte die Fragen des Nutzers zu Kunden. Nutze dafür die verfügbaren Tools. Fasse die Ergebnisse verständlich zusammen.
```

## Additional Context

Bleibt leer.

---

## Tool-Beschreibungen

**Calculator**

```
Führt mathematische Berechnungen aus.
```

**MCP-Server `workshop-docs`**

```
Durchsucht Projektdokumentationen, Abnahmeprotokolle, Gesprächsnotizen und Mailverläufe der Norbach Antriebstechnik.
```

**Joule Skill `Get Customer Master Data`**

```
Returns master data for a customer of Norbach Antriebstechnik by customer name, including customer ID, industry, key account manager, year-to-date revenue and payment terms. Returns multiple results if several customers match the name.
```

**Joule Skill `Get Open Opportunities`**

```
Returns all open sales opportunities for a given customer ID of Norbach Antriebstechnik, including title, value, currency, probability, sales phase and expected close date.
```

---

## Testfragen

| # | Frage |
|---|---|
| T1 | Bereite mir den Termin mit Halstrom Anlagenbau vor. |
| T2 | Wie hoch ist unser gewichteter Pipeline-Wert bei Halstrom? |
| T3 | Was weißt du über Kessler Systemtechnik? |
| T4 | Welchen Preis können wir Halstrom zusagen? |
