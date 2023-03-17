### IRS
#### Integriertes Redaktionssystem
- ersetzt end-of-life System Gideon<!-- .element: class="fragment" -->
- bildet den gesamten Erstellungsprozess einer Biographie ab<!-- .element: class="fragment" -->
- baut auf erprobte open-source Technologien auf<!-- .element: class="fragment" -->
- ...und wird unter der MIT Lizenz (open-source) veröffentlicht<!-- .element: class="fragment" -->

Note:
- Gideon teuer, nur auf IE, wird von Fikrma nicht mehr entwickelt
- open-source wichtig:
    - kein log in Effekt
    - of viele existierende plugins
- MIT Lizenz eine der offensten Softwarelizenzen

+++

<span class="fragment"></span>
<span class="fragment"></span>
<span class="fragment"></span>
<span class="fragment"></span>

<div data-animate data-src="images/irs_structure_de.drawio.svg">
<!--
{ "setup": [
{ "element": "#cell-5, #cell-14, #cell-6, #cell-15, #cell-16, #cell-7, #cell-17, #cell-8, #cell-9, #cell-2", "modifier": "attr", "parameters": [ {"class": "fragment", "data-fragment-index": "0"} ] },
{ "element": "#cell-12, #cell-3, #cell-10", "modifier": "attr", "parameters": [ {"class": "fragment", "data-fragment-index": "1"} ] },
{ "element": "#cell-13, #cell-4, #cell-11", "modifier": "attr", "parameters": [ {"class": "fragment", "data-fragment-index": "2"} ] },
{ "element": "#cell-25, #cell-24", "modifier": "attr", "parameters": [ {"class": "fragment", "data-fragment-index": "3"} ] }
]}
-->
</div>

Note:
- Researchtool:
    - Datenbank für die Recherche
    - ~100.000 KandidatInnen aus Gideon werden importiert
    - Auswahl hier, dann drag and drop auf 'Lieferung'
- Workflowtool:
    - daadurch import ins Workflowtool
    - Abbildung des Redaktionsprozesses
    - von Detailseite jeder Bio Zugang Editor
- Editor:
    - Verfassen der Bio
- Webpage:
    - aus dem Workflowtool dann Veröffentlichung -> webpage 



+++

### Zeitrahmen
- Erste Alpha Version inklusive aller Komponenten Q2<!-- .element: class="fragment" -->
- Beta Ende Q3<!-- .element: class="fragment" -->
- produktives System Ende 2023<!-- .element: class="fragment" -->

Note:
- schon jetzt alle Komponenten zu Testzwecken auf Servern

---

## aktueller Status

+++

### IRS Researchtool

<img class="r-stretch" style="margin-bottom:60px" src="images/screenshot_irs_researchtool.png">

Note:
- Liste aller Kandidaten
- Daten in Tabelle, Spalten konfigurierbar
- Referenzen in Zotero
- externe Dateien anfügbar
- Suche in allen Feldern
- Detailseite rechts
- frei konfigurierbare Listen links
- import aus z.b. Excel
- semiautomatisches Mapping auf GND
- automatische scrape jobs im Hintergrund

+++

### IRS Workflowtool

<img class="r-stretch" style="margin-bottom:60px" src="images/screenshot_irs_workflow_2.png">

Note:
- import aus researchtool via drag and drop
- Spalten: redaktioneller Prozess
- Etiketten: organisatorisch/formelles: vertrag, Bezahlung etc
- einfaches drag and drop
- rechts Details einer Bio (metadataen, status etc)
- zugang zu Editor

+++

### IRS Editor

<div class="r-stretch" style="display: flex;">
<img style="margin-bottom:60px; flex: 1; margin-right: 5px;" src="images/screenshot-irs-editor-v1.png">
<img class="fragment" data-fragment-index="1" style="margin-bottom:60px; flex: 1; margin-left: 5px" src="images/screenshot-irs-editor-v2.png">
</div>

Note:
- nur die Wichtigsten Funktionen
- Annotation
- Kommentarfunktion
- Versionierung
- detailiertes Rechtemanagement: write, view, comment
- Autoren bekommen einfach Link (ähnlich Google Docs)

+++

### ÖBL Webpage neu

<div class="r-stack">
<img class="fragment fade-out" data-fragment-index="0" style="margin-bottom: 550px" src="images/screenshot-oebl-apis-search.png">
<img class="fragment current-visible" style="margin-bottom: 35px" data-fragment-index="0" src="images/screenshot_oebl_aigner_page.png">
</div>

Note:
- einfacher Suchschlitz + Facettierung
- Suche lemmatisiert und sucht auch via Synonyme (via GND udn Wikidata erstellt)
- Annotationen -> in Zukunft auch mit Metadaten im Overlay
- Medien: Bilder, Audio, Video
- Visualisierungen: Lifeline, Karte, vielleicht Netzwerk