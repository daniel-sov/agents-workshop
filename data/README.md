# Unterlagen der Norbach Antriebstechnik

Das hier ist Nachschlagematerial, keine Arbeitsanweisung. Die steht in der Challenge.

Auf genau diese Unterlagen greift euer Agent zu. Schaut rein, bevor ihr ihm glaubt:
Wenn er etwas behauptet, das hier nicht steht, hat er es erfunden.

## Was es zu welchem Kunden gibt

| Kunde | Kundennummer | Opportunities | Bestellungen | Dokumente | Kommunikation |
|---|---|---|---|---|---|
| Halstrom Anlagenbau GmbH | `C-10042` | 11 | 3 | 4 | 3 |
| Halstrom Service GmbH | `C-10043` | 1 | 1 | 1 | 1 |
| Kessler Systemtechnik GmbH | `C-10077` | 0 | 0 | 0 | 0 |
| Brandtner Fördertechnik AG | `C-10015` | 2 | 1 | 1 | 1 |
| Vogelsang Prüftechnik GmbH | `C-10061` | 1 | 0 | 1 | 0 |

## Wo was liegt

| Ordner | Inhalt | Der Agent sieht das über |
|---|---|---|
| `CRM/` | `CRM-Export Norbach Antriebstechnik.xlsx`, drei Tabellenblätter | die beiden Joule Skills |
| `Projektdokumente/` | Abnahmeprotokolle, Projektdoku, Gesprächsnotizen als PDF | `search_project_docs` und `get_document` |
| `Kundenkommunikation/` | Mailverläufe und Telefonnotizen als PDF | `search_communication` |

Die Dokument- und Vorgangsnummern in den Dateinamen sind dieselben, die der Agent
in seinen Antworten nennt. Darüber könnt ihr jede Aussage nachschlagen.

Alle Daten sind frei erfunden. Die Norbach Antriebstechnik GmbH gibt es nicht.
