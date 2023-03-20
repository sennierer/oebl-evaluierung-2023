### Technische Ziele des ÖBL
- einheitliches Redaktionssystem um den gesamten Redaktionsprozess abbilden zu können<!-- .element: class="fragment" -->
- tiefere Einbindung der Linked Open Data Cloud (LOD)<!-- .element: class="fragment" -->
- mehr strukturierte, maschinenlesbare Daten<!-- .element: class="fragment" -->
- Veröffentlichung dieser Daten unter Berücksichtigung von best practices und Standards<!-- .element: class="fragment" -->

Note:
- Effizients, Nachverfolgbarkeit des Redaktionsprozesses
- Wiederverwendung vorhandener Daten (passiert zum Teil schon), Andockstellen für andere Datensätze (URIs)
- alle Teile einbinden: Bibliographie, Versionen, Relationen
- FAIR principles der Daten: findable, acessible, interoperable, reuseable

+++

### Vorhandene Tools und Daten
- Gideon: Java/oracleDB basiertes Redaktionssystem<!-- .element: class="fragment" -->
- XML Dateien (Retrodigitalisierung & seit 2008 born-digital)<!-- .element: class="fragment" -->
- APIS Datenbank (aus APIS Projekt: 2015-2020)<!-- .element: class="fragment" -->

Note:
- APIS System wird in ~ 10 Projekten am ACDH-CH eingesetzt

+++

### Geplante Schritte
- IRS: Integriertes Redaktionssystem<!-- .element: class="fragment" -->
- verbesserte ÖBL webpage<!-- .element: class="fragment" -->
- Wiederverwendung der Daten in anderen Projekten -> InTaVia<!-- .element: class="fragment" -->
- aktives Engagement im wikipedia/wikidata Umfeld<!-- .element: class="fragment" -->

Note:
- IRS basiert auf APIS als Backend, zusätzlich Workflow Komponenten auf den Servern die jobs abarbeiten
- ÖBL webpage:
- Export der Daten -> Konvertierung in Pipelines (prefect) -> anderes Projekt
- vorallem wikidata: automatische Anreicherung der Datensätze mit ÖBL Daten -> API -> Konvertierung in Pipeline -> Wikidata. wikipedia: automatisches Hinzufügen des ÖBL Links?