# Lernjournal.Module162

Heute (18.08.2025) haben wir uns im Gitlab eingeloggt. Da es bei mir nicht funktioniert hat, habe ich mich stadtdessen bei Github angemeldet.
Danach haben wir das [Markdown Tutorial](https://www.markdowntutorial.com/de/lesson/1/) angefangen


(25.08.2025) **Zusammenfassung Strukturierte Daten**    
Datenstruktur: Objekt zur Speicherung und Organisation von Daten  
Strukturierte Daten: Grundform (Tabelle, Kette...)  
Einordnung: semi-strukturierte Daten haben kein Datenmodell aber eine gewisse Struktur (z.m.B Mail)
Unstrukturierte Daten 

[**Skalentypen**](https://gitlab.com/ch-tbz-it/Stud/m162/-/raw/main/Daten_Formate/images/Skalenniveaus.jpg)
Nominalskala: Keine Rangordnung/ alle gleichwertig  
Ordinalskala: Rangordnung  
Kardinalskala: Rangordnung/ Abstände sind interpretierbar (z.m.B L)  


**Schweizer Datenschutzgesetz**  
•Wann tritt das neue Schweizer Datenschutzgesetz(DSG) in Kraft?  
* 01, September 2023
 
     
•In welchen Fällen müssen Verantwortliche mit Sitz im Ausland einen Schweiz-Vertreter benennen?    
* Verarbeitung steht im Zusammenhang mit dem Angebot der Waren oder Dienstleistungen in der Schweiz.
* Die Verarbeitung personbezogener Daten ist umfangreich und findet regelmässig statt.
* Die Verarbeitung führt wahrscheinlich zu einem hohen Risiko für die Privatsphäre der betroffenen Person.


**Lizenzmodelle**  
Erklären Sie das Wort Lizenz. Was bedeutet das?   
* Offiziele Erlaubnis etwas zu machen/ zu besitzen  
Warum kommt man auf die Idee, Lizenzen zu schaffen?  
* Um Unfälle und Gefährliches zu vermeiden (z.m.B Führerschein)  
Worauf gibt es alles Lizenzen ausser für Software?  
* Es gibt Lizenzen für Berufe und Tätigkeiten wie fahren und fliegen.
Machen Sie eine Aufzählung von Lizenzmodellen.
* Proprietäre Software
* FOSS/ Open Source
* Volumenlizenz
* CSP/ Cloud Solution Provider
* OEM
* PKC/ Product Key Card
* FPP/ Full packaged Product
  
Was bedeutet "open source" und was kann man mit solcher Software machen?  
* Es bedeutet "Offene Quelle" und es ist dafür gemacht, dass eine Software öffentlich, also zugänglich für die Öffentlichkeit ist.
* 
Was ist der Unterschied zwischen "copyright" und "copyleft"?
*   Copyright beschützt ein Werk, so das es ohne Erlaubnis nicht benutzt oder bearbeitet werden kann.
*   Copyleft ist dafür, das man ein Werk frei nutzen und teilen kann. Also sollte es man nur nutzen, wenn man es wieder teilt.

  
  Welches Lizenz-Modell wird angewendet, wenn man 
	- im App-Store eine zu bezahlende App heunterlädt und installiert?
	- im App-Store eine Gratis-App heunterlädt und installiert?
	- Haben Sie die Software bezahlt, als Sie ihr aktuelles Smartphone gekauft/bekommen haben? Wenn Sie es nicht wissen, ob Sie extra bezahlt haben, wie und wann bezahlen Sie?
 * Bezahlbare App: EULA, also eine Art "Vertrag" zwischen dem Anbieter und mir
 * Gratis App: Freeware, Lizenz zur Nutzung 
 * Bei einem iPhone sind die Lizenzkosten im Preis schon mitberechnet (Apple iOS EULA).

   
(01.09.2025)**Einfache Datentypen**   

| Wert                                           | Datentype(n) |
| ---------------------------------------------- | ------------ |
| A                                              | Zeichen                         |
| 23                                             | Ganze/ Natürliche Zahl          |
| 12021.25                                       | Dezimalzahl                     |
| 0                                              | Ganze/ Natürliche Zahl, Boolean |
| Ciara                                          | Zeichnenkette                   |
| 12.2341235211                                  | DECIMAL                         |
| true                                           | BOOLEAN                         |
| oben,unten                                     | ENUM                            |
| .f},ÌúþÃ¸ìîìbõ©/=¹ryïòƒÇâ‘hðÂ.š¿ã‘q            | TEXT                            |
| {name: "Meier", vorname: "Maxwell", alter: 21} |                                 |


Ganze Zahlen: BIGINT, INT, INTEGER, LONG, SHORT   
Natürliche Zahlen: NATURAL   
Festkommazahlen (Dezimalzahlen): DECIMAL, NUMERIC   
Aufzählungstypen: ENUM, SET   
Boolean (logische Werte): BOOL, BOOLEAN   
Zeichen (einzelnes Zeichen): CHAR, CHARACTER   
Gleitkommazahlen: DOUBLE, FLOAT   
ARRAY   
DATE, TIME, DATETIME, TIMESTAMP   


**Datensatz**   
Verkörpern Werte, die andere Werte enthalten. Üblichwerweise in einer fest definierten Anzahl und Folge.   
Bsp. (ID=12, Vorname=Hans)

**Array**   
Speichert mehrere Variablen vom selbem Datentyp. Zugriff auf die einzelne Elemente wird über einen Index möglich.   
Bsp. (12, 45, 38, 28)

**Verkettete Liste**   
Datenstruktur zur dynamischen Speicherung von beliebig vielen Objekten. Jedes Listenelement beinhaltet einen Verweis auf das nächste Element.   
Analogie: Zug-Komposition. Die Wagen sind jeweils verbunden.

**Stapelspeicher/ Stack**   
In einem Stapelspeicher kann man nur das letzt hinzugefügte wieder entfernen/ lesen. (LIFO-Prinzip= Last in-First out)   
Analogie: Im Bus, der letzte der reingeht muss als erstes raus.

**Warteschlange**   
In einer Warteschlange können die Objekte nur in der Reihenfolge gelesen werden, in der sie gespeichert worden sind. (FIFO-Prinzip= First in-First out)    

**Vorrangwarteschlange**   
Eine Spezialisierung der Warteschlange. Dabei wird das Objekt gemäss einer gegebenen Priotität sortiert.   
Analogie: Warteschlange vor CLUB/ Disko mit VIP-Liste

**Graph**   
Ermöglicht, eine Referenz auf mehrere Objekte zu halten.   
Analogie: GPS Navigationssystem mit Wegen und Zeiten.

**Baum**   
Besitzten eine eingehende Verknüpfung, aber mehrere ausgehende Verknüpfungen.
Bsp. Dateisystem auf dem Computer.

**Heap**   
Vereint die Datenstruktur eines Baums mit der der Vorrangwarteschlange.    
Analogie: Warteschlange nach Priorität(z.m.B Krankenhaus).

**Hashtabelle**
Eine Tabelle in der die Speicherposition direkt berechnet werden kann. Man gibt einen Schlüssel ein (z.m.B "Name") und er sagt dir direkt, wo er liegt(z.m.B Index 1 = steht die "Telefonnummer" von "Name").   
Analogie: Buchregal, jedes Buch hat einen Code und ein Regal, in das er gehört. Das Hash System zeigt diese Informationen, wenn man den Namen(Schlüssel) des Buches eingibt.
