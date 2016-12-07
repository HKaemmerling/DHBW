# Session 4 (21. + 24.11.2016)




### Contact und Account Management
* Stammdatenpflege
* Transaktionsdaten
  * was für Käufe
  * **Product Lifecyle** (nach welcher Spanne kauft mein Kunde das Produkt wieder?)
* via **touchpoints** (überall, wo man mit dem Kunden in Kontakt tritt)

### Sales
* Cross selling:
  * ergänzendes Produkt
* Up Selling:
  * höherwertiges Produkt

### Marketing
* Kampagnen-Management
* Kundeneinteilung (in Segmente/Zielgruppen)
* Analyse der Kundenreaktion/-antwort
* Abarbeiten der Kundenanfragen

### Service und Support
* Kunden und eigene Performance monitoren
* **service request handling**
  * wie reagiere ich auf Serviceanfragen?
* **Complaint Management**:
  * wie reagiere ich auf Beschwerden?
* z.B. via Call Center oder Helpdesk

### Relation und Loyality
* profitable Kunden identifizieren und ggf. "belohnen"



## Architektur des CRM
* Im Mark interagieren:
  * Collaborative CRM
    * direkter Kontakt zum Kunden
    * **ohne** IT-System
* Mit IT-System interagieren:
  * Operative CRM
    * front office
    * Geschäftsprozesse
    * facing via touching points
  * Analytical CRM
    * Daten auswerten/analysieren
    * **Datenbank**
    * via:
      * Data Mining
      * Decision Support
      * OLAP
      * Business intelligence
* alle 3 Bereiche tauschen Informationen aus (arbeiten aufeinander abgetimmt)


------------------------------------------------

## Supply Chain
* Versorgungskette
  * Fluss von Material, Informationen, Geld, Dienstleistungen
  * z.B.: Rohmaterial &rarr; Produktion, Vertrieb, ... &rarr; Endkunde
  * vom Anfang bis zum Ende
* Bsp.: http://images.google.de/imgres?imgurl=https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/Integration_in_Deutsch.svg/220px-Integration_in_Deutsch.svg.png&imgrefurl=https://de.wikipedia.org/wiki/Vertikale_Integration&h=177&w=220&tbnid=3j0gzsNfRf95UM:&vet=1&tbnh=141&tbnw=176&docid=-MKGN-apLgG3XM&usg=__XbhoNszKYkxQMhyu2DnAcQGwa9Q=&sa=X&ved=0ahUKEwiIsdfN8cPQAhUqBMAKHYAPBlUQ9QEIIDAA
*  Ziele:
  * enge vertikale Integration (mit Lieferanten und Abnehmern)
  * nicht isoliert sein
  * &rarr; vernetzt (gute Konatkte/Beziehungen)
  * **Fokus auf eigene Kernkompetenzen legen**
  * visibility
  * höhere Flüchtigkeit des eigenen Inventars (**Just-in-time Lieferung**) &rarr; weniger gebundenes Kapital
  * wissen, wo meine Produkte herkommen (Bsp.: Tier 3 Supplier &rarr; Tier 2 Supplier &rarr; Tier 1 Supplier)
  * &rarr; woher beziehe ich meine Güter
  * Früh auf Änderung reagieren (z.B. wenn Tier 3 Supplier ein Problem hat und das bald einen selbst betreffen wird)
  * wichtige Begriffe: upstream, downstream, internal, flows

### Supply Chain Life Cycle
1. commit:
  * Auftrag, Bestätigung, Rahmenvertrag, ...
  * **Verpflichtung**
2. schedule:
  * Planung (bei commitment schon Datum nennen)
3. deliver:
  * Datum/Frist einhalten


### SCM Lösung (System)
* Datenbank
  * Teil der Datenbank für Supplier, Retailer, Kunde verfügbar
  * reduziert und zugeschnitten
  * &rarr; relevante Informationen sind für authorisierte Nutzer verfügbar

### SCM Management
* planen
* Verbessern
* organisieren
* &rarr; günstiger einkaufen, besser produzieren, schneller liefern


### SCM Prozesse
* planen (plan)
* beziehen (source)
* produzieren (make)
* liefern (deliver)
* zurück (return)

### SCM Informationssystem
* **organisationsübergreifend**
* Ziele:
  * Geschäftskosten bei Transaktionen reduzieren
  * Qualität verbessern / Fehler reduzieren
  * schneller produzieren / liefern
  * Papier sparen
  * Daten einfacher austauschen / anderen verfügbar machen
  * &rarr; Zeitsparen / Reibungen in Supply Chain reduzieren / vermeiden

### Arten der Reibung (Friction)
* schlechter Kundenservice (Zufriedenheit)
* langsame / zu späte Lieferung (Verzögerungen)
* Probleme mit dem Inventar (zu groß &rarr; gebundenes Kapital &rarr; weniger Umsatz)

### Probleme
1. Unsicherheiten (Zukunft, Risiken, Schwankungen)
  * bullwhip effect
    * Auswirkungen entlang der Versorgungskette vergrößern sich (z.B. bei Ausfällen bei Tier 3 Supplier)
    * Probleme werden entlang der Kette größer
2. Kommunikation
  * Geheimhaltung
  * Austausch von Informationen zwischen Geschäftspartnern nicht selbstverständlich (Interessen werden abgewägt / Informationen = competitive advantage)
  * Herrschaftswissen
  * Protektionismus

### Lösungen
* **Just-in-time-inventory (JIT)**
  * Versorgungssicherheit
  * geplant
  * Inventar verkleinern
* **Informationsharing**
  * Bsp.: Vendor Management Inventory (VMI)
    * Lieferant für mein Inventar verantwortlich
    * bezahlt wird bei Verbrauch
    * Bestand beim Kunden gehört dem Lieferanten
    * Vorteile für den Kunden:
      * Flexibilität
      * kein gebundenes Kapital
    * Vorteile für den Lieferanten:
      * höhere Preis (Ausgleich für Risiken)
      * Kunde ist gebunden

### Technologischer Support für SCM
1. EDI: Electronical Data Interchange
  * geminsamer Datenstandard (Vordefiniertes EDI Format) für Dokumente / Informationsaustausch
2. Extranet
  * Zugang für authorisierte Geschäftspartner im Intranet
  * via VPN
3. Portals + Collaboration Exchanges
  * Procurement Portals (für supplier (upstream))
  * Distribution portals (für customer (downstream))

### Manuell (ohne EDI)
* **aufwenig**
* anfällig
* viele Schwachstellen

### Mit EDI
* strukturiert
* automatisiert
* **effizient**

## Push vs Pull Modell
### Push Modell
* **make to stock**
* Massenproduktion
* nach Vorhersagen
* auf Markt "drücken"
* Bsp.: Getränke, Lebensmittel, Kleidung
### Pull Modell
* **Make to order**
* warten, bis Auftra da ist
* &rarr; Auftrag liegt vor
* Customization
* Serienproduktion
* Bsp.: Autos
### Make to customize
* Bsp.: Schiffe


## Business Analytics Information Systems
* für Top Level  Managament
* wie effektiv bin ich (Input/Output Ratio)

### Schwierigkeiten
* viele Informationen (Big Data)
* Zeitdruck (gegen Konkurrenten)
* gute Analysen werden benötigt (korrekte)
* brauche Informationen schnell (Experten bereiten Informationen auf)
* Befehle werden nach unten kaskadiert
* Informationen werden nach oben aggregiert

### Lösungen Business Intelligence Tools (BI)
* Überbegriff für Technologie, Prozesse, Systeme, die Entscheidungen unterstützen (Bsp.: Excel (das Wichtigste)) (Data Mart/Data Warehouse)
1. multidimensional / OLAP
  * gesichert
  * die Daten so, wie ich sie haben will rausholen
  * slicing und dicing
2. Data Mining
  * Trends
  * Kundenverhalten
  * unbekannte Zusammenhänge
  * Vorhersagen
  * Betrug vorbeugen
3. Decision Support System DSS
  * Kombination von Daten
  * &rarr; Mathematische Funktionen
  * Daten verstehen &rarr; Markt verstehen
  * Sensivity Analysis:
    * wie abhängig ist mein Ergebnis von einer Variable (Preis, Qualität, ...)
    * woran liegts
  * What-if-Analysis:
    * Annahmen treffen
    * wenn..., dann...
    * Vorhersagen
  * Goal Seeking Analysis:
    * was muss ich für mein Ziel tuen


### BI Representing Reports
1. Dashboards
  * UI (schöne Grafik)
  * einfach darstellen (Trends)
2. Data Vizualization Technologie
  * Grafiken / Tabellen
  * einfacher zu verstehen
3. Real Time BI
  * **So früh wie möglich**
  * multidimensionale Analyse
  * Data Mining
  * &rarr; Entscheidungen unterstützen


### CPM Corporate Performance Management
* Monitoring:
  * Prozesse
  * Kunden
* &rarr; darstellen /auswerten
* &rarr; KPI (Key Performance Indikators (das allerwichtigste))

## E-commerce
* kaufen
* verkaufen
* übertragen
* Austausch von
  * Dienstleistungen
  * Informationen
  * Produkten
* **via Computer Systeme (+Internet)**

### Einfluss auf Unternehmen
* höhere Reichweite
* Expansion ohne Realpräsenz möglich
* &rarr; online (virtuelle) Präsenz
* geringere Eintrittsbarrieren (z.B. für Start-Ups)
* verändert drastisch die Natur des Wettbewerbs
* **&rarr; überlebenswichtig für jedes Unternehmen (critical)**

### Strategie (Warum e-commerce?)
* verkaufen von Waren / Dienstleistungen
* Werbung für Vor-Ort-Verkauf
* Operations- / Transaktionskosten verringern
* Ruf / Image verbessern

### Erfolgsfaktoren (Was brauche ich?)
* Einfache Nutzung für Kunden (schönes / gutes UI)
* angenehmes Erlebnis (look and feel)
* Alternativen anbieten
* wettbewerbsfähiger Preis
* Zufriedenheit
* schnell
* zuverlässig
* Sicherheit für Transaktionen (Secure Sockets Layer SSL Zertifikate (z.B. für Zahlungen))

### Arten des e-commerce
* B2C
* B2B
* B2E
* C2C
* G2B
* G2C
* m-commerce

### Mechanismen
* Electronic Catalog (Backbone von e-commerce sites)
  * Produktdatenbank
  * Präsentaionsfunktion
  * "Schaufenster"
* Electronic Auction
  *  geringe Kosten für den Verkäufer
  * forward auction:
    * Grundpreis &rarr; dann entscheiden Kunden (z.B. ebay)
  * reverse auction:
    * Request for Quotation (RFQ)


### E-Payments
* e-check
* e-creditcard
* virtual creditcard
* purchasing cards
* Store Value Money Cards
* Smart Cards


## B2C
* Business to Consumer
* viele Kunden
* "wenig" Anbieter (im Vergleich zu Kunden)
* viele Transktionen (Datenverkehr)
* Plattform muss für die Kapazitäten geeignet sein

### Vorteile
* sofortiges Feedback (&rarr; Gefühl des wichtigsten Kunden)
* direkter Kontakt
* sehen, wo meine Sendung ist
* einfach und schnell

### E-Storefront
* Website repräsentiert Laden
* eigen URL pro Storefront
* kann auch Erweiterung zum physischen Laden sein


### E-Mall (auch cybermall / electronic mall)
* Sammlung von shops zusammengeführt
* viele Anbieter
* Referall mall:
  * kein Verkauf nur Repräsentation
  * weiterleitung zum eigentlichen Anbieter
  * mehrere Transaktionen
* Electronic Shopping Cart:
  * von mehreren Shops kaufen aber nur eine Transaktion am Ende


### Challenges
* **Channel-Conflict:**
  * Problem: Kunden kaufen nur noch online bei mir
  * Nicht im physical Store
  * Konkurrenz: Online Shopping vs. Laden
  * Frage: Was ist mir wichtiger? (Prioritäten)
  * Ansätze:
    * Pricing (Preisanzeige und Verkauf nur im Laden möglich)
      * Ziel: Kunden in Laden holen
    * Ressourcenverteilung: Wo muss ich Geld investieren? (Wo lohnt es sich mehr?)
* **Order Fullfillment:**
  * Produkte (Bestellungen) an alle Kunden schicken
  * schnell und zuverlässig
  * geringe Fehlerquote
  * Bestellungen sortieren
  * hohe Datenmenge / Auftragsvolumen


## B2B
* Supply Chain verbessern
* digitalisieren
* Komplexität
* viele Beziehungen


### Sales Offerings
* **e-marketplace / central virtual market:**
  * sell-side:
    * anpassbar
    * forward auctions
    * private e-marketplaces
    * customization
    * Verkäufer : Hersteller, Distibuter, Retailer
  * buy-side:
    * Angebote suchen
    * reverse-auctions
    * group purchases
* **Electronic Exchanges:**
  * ein Käufer, viele Verkäufer
  * public Exchanges
  * vertikal: in einer Industrie
  * horizontal: industrieübergereifend
  * funktional: "as-needed-base"

## E-business
### Arten
* e-banking / cyberbanking
* online securities trading (Bsp.: Bloomberg)
* Job Matching (linked-in)
* Travel Services
* Advertising

### Benefits
* **Organizational:**
  * Verfügbarkeit
  * Kostensenkung
* **Customer:**
  * Kundenvorteile
    * ich kann eine größere Zahl an Kunden adressieren
    * mehr Produkte / Dienstleistungen anbieten
* **Societal:**
  * informationsharing

### Limitations
* **Technological:**
  * kein universal akzeptierter Standard
  * konkurrierende Standards
  * (Bandbreite)
* **Non-Technological:**
  * "Unsicherheiten" (wird noch als unsicher angesehen ("Neuland"))
  * unsolved legal issues

### Ethische Probleme
* **Data Privacy:**
  * Kundeninformationen schützen
  * cookies
* **Domain Tasting:**
  * Domain für 5 Tage kostenfrei reservieren
  * &rarr; ohne Investition Geld verdienen
  * Bsp.:
    * User klickt unabsichtlich eine Seite (werbeeinnahmen)
    * Seiten werden "Kopiert"
    * 0 Risiko für Betreiber
  * scam

### Legal Issues
* **Information Fraud:**
  * absichtliches Verbreiten von Falschinformationen
  * Stock informationen fraud
    * falsche Informationen zum Börsenwert verbreiten (börsenwertrelevante Falschinformationen)
    * sehr vulatiler Markt
    * &rarr; Manipulation
  * auction fraud (Käufer und Verkäufer)
  * falsche Informationen verkaufen
  * scam
  * &rarr; strafbar
* **Domain names:**
  * Wettbewerb um "beste" URL (wer zuerst kauft)
  * 2 Unternehmen haben gleichen Namen (z.B. sap.de)
* **Cybersquatting:**
  * domain für falschen Zweck benutzen &rarr; Profit
  * domain reservieren und dann verkaufen
* **Steuern und Zölle:**
  * keine einheitlichen Regeln
  * verschiedene Steuersätze
  * Wo wird Steuer gezahlt (beim Verkäufer, Käufer oder Server?)
* **Copyright:**
  * Linzenen online kaufen:
    * nur Nutzungsrecht
    * kein Eigentum
    * dürfen nicht weiter verbreitet werden
  * Intelectual Copyright Protections

## M-Commerce
* e-commerce auf mobilen Endgeräten
* Vorteil:
  * Produkte und Services an neue Art von Kunden verkaufen
  * flexibel und mobil
  * Kunde ist erreichbar, während er unterwegs ist
  * &rarr; neue Möglichkeiten

### Geräte (Drivers)
* immer mehr Geräte &rarr; availability
* Preise sinken immer mehr
* erhöhte Bandbreite (LTE / 4G)
* &rarr; schneller, besser, günstiger, mehr Daten

### Applikationen
* **positionsabhängig:**
  * Maps
  * Orte finden (nächster ATM, Restaurant)
  * Sportaktivitäten tracken
  * Freunde finden
  * Benachrichtigungen (Stau, Wetter)
* **Finacial Applications:**
  * Banking
  * Kontaktlose Bezahlen (Wireless Payments, money tranfser) (z.B. via NFC)
  * Taxi Payments
  * Bill Payments (OCR Optical Character Recognition)
  * &rarr; bezahlen (&rarr; kaufen) von überall
* **Intrabusiness Applications:**
  * Transport
  * Healthcare
  * Security
  * Field Service
  * Mobiles Arbeiten
* **Acessing Information:**
  * aggregierte Informationen auf meinem mobilen Gerät
  * Daten
  * Mobile Portale (zum Kauf animieren / Kaufverhalten tracken)
  * Voice Portale (Sprachassistent)
* **Telemetric Applications:**
  * Drahtlose Übertragung auf Basis von Sensoren
  * Bsp.: Find my iPhone
