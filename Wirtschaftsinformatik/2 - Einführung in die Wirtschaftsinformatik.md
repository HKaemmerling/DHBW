# Einführung in die Wirtschaftsinformatik (03.11.2016)

## Datenverarbeitung

### Daten
* ohne Kontext
* haben je nach Kontext verschiedene Bedeutungen

### Informationen
* Daten mit Kontext

### wissen
* Informationen, die für mich nutzbar sind
* --> Wettbewerbsvorteil
* --> wichtig für Unternehmen (crucial)

### Ziel von Daten
* akkurat
* vollständig
* zeitgemäß
* konsistent
* zugänglich
* relevant
* --> wertvolle Daten
* Informationssysteme können helfen
  * erheben
  * analysieren
  * speichern
  * zugänglich machen
* --> Datenmanagement ist schwer und teuer

### Schwierigkeiten / Herausforderungen
* sehr viele Daten aus sehr vielen Quellen (Daten verdoppeln sich alle 2 Jahre)
* Daten verändern sich
  * alte Daten werdne obsolet
* Datensicherheit (Schutz gegen Verlust)
* Qualität der Daten
* Integrität
* Datenschutz
* verschiedene Prozesse haben versch Ansprüche an die Daten

### Data Governance (Ziel / Optimalfall)
* Informationen so managen, dass Daten im Unternehmen einheitlich und definiert sind
* wertvolle Daten verfügbar (für authorisierte Personen) und transparent machen
* Sammeln, verteilen, Schützen von Daten

### Master Data Management (Strategie, um Data Governance zu erreichen)
* einheitlicher Prozess für alle Prozesse (speichern, verwalten, austauschen, synchronisieren von Daten)
* Ziel: single version of truth (einheitliche (korrekte) Datenquelle)
  * für Stammdaten (Metadaten): gelten für mehrer Prozesse
  * für Transaktionsdaten: gelten für eine Transaktion


### Herkömmliche Datenquellen
* Memos
* Telefon
* Fax
* Webpages

### Neue Datenquellen
* Sensoren
* Pod-/Videocasts
* Blogs
* RFID tags
* social media

## Big Data

### Definition: variety, velosity, volume
* große Menge an flüctigen Daten, die sehr vielfältig sind
* viele Daten (hohe Menge)
* verschiedene Daten
* Flüchtigkeit (Daten verändern sich, verlieren schnell an Relevanz, nur kurzzeitig vorhanden --> ich muss direkt handeln)
* unstrukturiert

### Challenge
* wie gehen wir damit um
* strukturierte Daten sind einfacher zu verarbeiten
* können sehr wertvoll sein (strukturiert und analysiert)
* Verwaltung und Management der Daten ist schwierig
* Lösung:
  * mit wahrscheinlickeiten arbeiten
  * cognitive
  * Vorhersagen treffen

### Arten von Big Data
* Traditionelle Unternehmensdaten (Kundendaten müssen schnell verarbeitet werden)
* Maschinengenerierte Daten (z.B.  durch Sensoren)
* Social Data
* Bilder (Bsp: Nutzern können anhand von Bilder Werbung bekommen (auch Standortdaten))


### Nutzen von Big Data
1.  * transparenz
    * zeitnaher Zugriff
2.  * bessere Vorraussetzungen für Simulationen und Experimente
3.  * Kaufverhalten analysieren
    * Kundenkreis segmentieren
    * tailored products
4.  * menschliche Entscheidungen unterstützen (ersetzen)
5.  * neue Geschäftsmodelle (z.B. Daten von Autos nutzen)
6.  * mehr Daten generieren



## Datenbanken
### File Management System (alt):
* Infosilo für jede Abteilung
* keinen gesamten Plan für die Daten (abteilungsübergreifend)
* jede Anwendung hat andere Anforderungen
* --> **inkonsitent**

### Datenbank Management (neu):
* alle (authorisierten) haben Zugriff auf alle Daten
* --> weniger (bis keine) Redundanz, Isolation oder Inkonsitenz
* Vorteile:
  * nur eine Quelle, die geschützt werden muss (sicher)
  * Integrität
  * Unabhängigkeit (zwischen versch. Quellen, da keine Daten in verschieden Quellen)


## Datenhierarchie
* **Bit** : 0 oder 1
* **Byte** : 8 bit
* **Feld** : logische Gruppierung von Zeichen (z.B. Wort, ID, Gruppe von Wörtern)
* **Record** : Eintrag / logische Gruppe von Feldern (z.B. Tabelleneintrag --> Zeile)
* **File** : logische Gruppe von Records (z.B. Tabelle)
* **Datenbank** : Sammlung von Files (z.B. Tabellen)


## ER Modelling
* Ziel:
  * darstellen, wie Benutzer Aktivitäten definieren
  * Datenbanken planen
  * prüfen, ob alles vorhanden ist
  * Design der Datenbank
* --> ER Diagramm mit Entitäten, Beziehungen,  Attributen (+ Schlüsselattribute), Kardinalitäten (in Normalform)


## Wichtige Begriffe (Klausur)
* **Datenmodell** : Formale Beschreibung Beziehungen untereinander
* **Entität** : Objekt aus Realität
* **Instanz** : Darstellungsform Entität (**ein** Objekt einer Entität &rarr; eindeutig)
* **Attribut** : Charakteristika der Entität
* **Primärschlüssel** : Eindeutiges Feld, dass einen Datensatz eindeutig identifiziert
* **Sekundärschlüssel** : Identifikation aber nicht 100% eindeutig
* **Fremdschlüssel** (!=Sekundärschlüssel)

* **&rarr;** Datenbank : jeder kann laden, analysieren, verstehen

## Datenbank Management
* Set von Programmen (add, access, modify, analyze)
* &rarr; effektiv, effizient
* Aufgaben:
  * maintain Data
  * manage security
  * Recover bei failure

## Datawarehouse (alles) (verwaltete durch Data Management System (unveränderbar)
* Ansammlung von historical data
* strategisch
* alles
* Ziel:
  * Daten den Konsumenten zur Verfügung stellen (detailliert und aus **allen** Datenbanken)
* &rarr; zentrale Kontrolle &rarr; Weitblick


!=


## Data Marts (auf aggregierten Teil spezialiesiert) (unveränderbar)
* themenbezogen
* weniger Daten
* zusammengefasst
* kontextbezogen
* aggregiert
* &rarr; Ziel: Dem Konsumenten spezifische Daten zur Verfügung zu stellen


## Wichtige Punkte bei Data Warehouse und Data Marts
* Zeitabhängig
* multidimensional
* OLAP nutzen &rarr; Online analytical prossecing
* integriert
* werden in der Regel nicht verändert





## Wo ist mein Wissen?
* **Wissen = intelektuelles Kapital**
* größtenteils nicht strukturiert in Datenbanken, Informationssystemen
* meist in:
  * Mails
  * Dokumenten
  * Präsentationen
  * User PCs
* **Folge** : es ist schwer ohne die benötigten Informationen Entscheidungen zu treffen

### Explizites Wissen
* **objektiv**, technisch
* rational
* **dokumentiert** (&rarr; ständig abrufbar)
* liegt vor

### Implizites Wissen (tacit) (**oft wichtiger** (crucial))
* **subjektiv**
* experimentiell
* Erfahrungswerte
* unstrukturiert
* schwer transferierbar
* nicht dokumentiert
* liegt nicht allen vor
* in den Köpfen meiner Mitarbeiter

# Wissensmanagement  
