# Leśne mapowanie – twórz, analizuj, odkrywaj

Materiały do warsztatu na Dniu Jakości Kształcenia, Uniwersytet Rolniczy im. Hugona Kołłątaja w Krakowie, 17.11.2026, sala komputerowa nr 154.

Wersje językowe: [polski](#polski) · [English](#english) · [slovenčina](#slovenčina)

---

## Polski

### Zawartość repozytorium

| Folder | Zawartość |
|---|---|
| `slajdy/` | Prezentacja warsztatu (PL, EN, SK) |
| `konspekt_ArcGIS_Pro/` | Konspekt krok po kroku dla ArcGIS Pro (PL, EN, SK), PDF do druku dwustronnego |
| `konspekt_QGIS_wersja_dodatkowa/` | Konspekt krok po kroku dla QGIS (PL, EN, SK) |
| `sciaga_ArcGIS_Pro/` | Ściąga: narzędzia NMT, nawigacja po mapie i skróty klawiszowe w ArcGIS Pro (PL, EN, SK) |
| `dane/` | Dane do ćwiczenia: jedno archiwum ZIP na obiekt |
| `kod_QR/` | Kod QR prowadzący do tego repozytorium |

### Obiekty i dane

Każdy uczestnik wybiera jeden obiekt i pracuje na czterech arkuszach NMT.

| Archiwum | Obiekt | Arkusze NMT (godła) |
|---|---|---|
| `01_Data_Szczebrzeszyn.zip` | Wąwóz pod koronami drzew – Roztocze Szczebrzeszyńskie, okolice Szczebrzeszyna | M-34-46-D-d-3-2, M-34-46-D-d-3-4, M-34-46-D-d-4-1, M-34-46-D-d-4-3 |
| `02_Data__Twierdza_Przemysl.zip` | Fort w lesie – Twierdza Przemyśl, Fort VII „Prałkowce” | M-34-82-C-b-4-1, M-34-82-C-b-4-2, M-34-82-C-b-4-3, M-34-82-C-b-4-4 |
| `03_Data_Radocyna.zip` | Struktura łanów w sośninach porolnych – Beskid Niski, okolice Radocyny | M-34-91-D-a-2-4, M-34-91-D-a-4-2, M-34-91-D-b-1-3, M-34-91-D-b-3-1 |

Format danych:

- numeryczny model terenu (NMT), format ARC/INFO ASCII GRID (`.asc`), siatka 1 m;
- układ współrzędnych poziomych PL-1992 (EPSG:2180), układ wysokości PL-EVRF2007-NH;
- brak danych: −9999;
- przy każdym arkuszu plik `.prj` z definicją układu PL-1992, dzięki któremu ArcGIS Pro i QGIS rozpoznają układ współrzędnych.

Źródło danych: państwowy zasób geodezyjny i kartograficzny (PZGiK), Główny Urząd Geodezji i Kartografii.
Mapy na slajdach z obiektami: usługa Krajowa Integracja Baz Danych Obiektów Topograficznych, Główny Urząd Geodezji i Kartografii.

### Kontakt

mgr inż. Jakub Miszczyszyn
Katedra Zarządzania Zasobami Leśnymi, Wydział Leśny, Uniwersytet Rolniczy im. Hugona Kołłątaja w Krakowie
www.miszczyszyn.org · kzzl.urk.edu.pl · jakub.miszczyszyn@urk.edu.pl

---

## English

### Repository contents

| Folder | Contents |
|---|---|
| `slajdy/` | Workshop presentation (PL, EN, SK) |
| `konspekt_ArcGIS_Pro/` | Step-by-step handout for ArcGIS Pro (PL, EN, SK), PDF for double-sided printing |
| `konspekt_QGIS_wersja_dodatkowa/` | Step-by-step handout for QGIS (PL, EN, SK) |
| `sciaga_ArcGIS_Pro/` | Cheat sheet: DTM tools, map navigation and keyboard shortcuts in ArcGIS Pro (PL, EN, SK) |
| `dane/` | Exercise data: one ZIP archive per site |
| `kod_QR/` | QR code linking to this repository |

### Sites and data

Each participant chooses one site and works with four DTM sheets.

| Archive | Site | DTM sheets |
|---|---|---|
| `01_Data_Szczebrzeszyn.zip` | A gully under the tree crowns – Szczebrzeszyn Roztocze, near Szczebrzeszyn | M-34-46-D-d-3-2, M-34-46-D-d-3-4, M-34-46-D-d-4-1, M-34-46-D-d-4-3 |
| `02_Data__Twierdza_Przemysl.zip` | A fort in the forest – Przemyśl Fortress, Fort VII “Prałkowce” | M-34-82-C-b-4-1, M-34-82-C-b-4-2, M-34-82-C-b-4-3, M-34-82-C-b-4-4 |
| `03_Data_Radocyna.zip` | Field strips in pine stands on former farmland – Low Beskids, near Radocyna | M-34-91-D-a-2-4, M-34-91-D-a-4-2, M-34-91-D-b-1-3, M-34-91-D-b-3-1 |

Data format:

- digital terrain model (DTM), ARC/INFO ASCII GRID format (`.asc`), 1 m grid;
- horizontal coordinate system PL-1992 (EPSG:2180), height system PL-EVRF2007-NH;
- NoData: −9999;
- each sheet has a `.prj` file with the PL-1992 definition, so ArcGIS Pro and QGIS recognise the coordinate system.

Data source: Polish National Geodetic and Cartographic Resource (PZGiK), Head Office of Geodesy and Cartography (GUGiK).
Maps on the site slides: Krajowa Integracja Baz Danych Obiektów Topograficznych service, GUGiK.

### Contact

Jakub Miszczyszyn, MSc Eng.
Department of Forest Resources Management, Faculty of Forestry, University of Agriculture in Krakow
www.miszczyszyn.org · kzzl.urk.edu.pl · jakub.miszczyszyn@urk.edu.pl

---

## Slovenčina

### Obsah repozitára

| Priečinok | Obsah |
|---|---|
| `slajdy/` | Prezentácia workshopu (PL, EN, SK) |
| `konspekt_ArcGIS_Pro/` | Postup krok za krokom pre ArcGIS Pro (PL, EN, SK), PDF na obojstrannú tlač |
| `konspekt_QGIS_wersja_dodatkowa/` | Postup krok za krokom pre QGIS (PL, EN, SK) |
| `sciaga_ArcGIS_Pro/` | Ťahák: nástroje DMR, navigácia v mape a klávesové skratky v ArcGIS Pro (PL, EN, SK) |
| `dane/` | Údaje na cvičenie: jeden archív ZIP na objekt |
| `kod_QR/` | QR kód s odkazom na tento repozitár |

### Objekty a údaje

Každý účastník si vyberie jeden objekt a pracuje so štyrmi hárkami DMR.

| Archív | Objekt | Hárky DMR |
|---|---|---|
| `01_Data_Szczebrzeszyn.zip` | Roklina pod korunami stromov – Roztocze Szczebrzeszyńskie, okolie Szczebrzeszyna | M-34-46-D-d-3-2, M-34-46-D-d-3-4, M-34-46-D-d-4-1, M-34-46-D-d-4-3 |
| `02_Data__Twierdza_Przemysl.zip` | Fort v lese – Pevnosť Przemyśl, Fort VII „Prałkowce“ | M-34-82-C-b-4-1, M-34-82-C-b-4-2, M-34-82-C-b-4-3, M-34-82-C-b-4-4 |
| `03_Data_Radocyna.zip` | Štruktúra lánov v borinách na bývalej poľnohospodárskej pôde – Nízke Beskydy, okolie obce Radocyna | M-34-91-D-a-2-4, M-34-91-D-a-4-2, M-34-91-D-b-1-3, M-34-91-D-b-3-1 |

Formát údajov:

- digitálny model reliéfu (DMR), formát ARC/INFO ASCII GRID (`.asc`), mriežka 1 m;
- horizontálny súradnicový systém PL-1992 (EPSG:2180), výškový systém PL-EVRF2007-NH;
- chýbajúce údaje: −9999;
- ku každému hárku patrí súbor `.prj` s definíciou systému PL-1992, vďaka ktorému ArcGIS Pro a QGIS rozpoznajú súradnicový systém.

Zdroj údajov: štátny geodetický a kartografický fond Poľska (PZGiK), Hlavný úrad geodézie a kartografie (GUGiK).
Mapy na snímkach s objektmi: služba Krajowa Integracja Baz Danych Obiektów Topograficznych, GUGiK.

### Kontakt

mgr inż. Jakub Miszczyszyn
Katedra manažmentu lesných zdrojov (Katedra Zarządzania Zasobami Leśnymi), Wydział Leśny, Uniwersytet Rolniczy im. Hugona Kołłątaja w Krakowie
www.miszczyszyn.org · kzzl.urk.edu.pl · jakub.miszczyszyn@urk.edu.pl
