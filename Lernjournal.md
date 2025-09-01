# Lernjournal.Module162

Heute (18.08.2025) haben wir uns im Gitlab eingeloggt. Da es bei mir nicht funktioniert hat, habe ich mich stadtdessen bei Github angemeldet.
Danach haben wir das [Markdown Tutorial](https://www.markdowntutorial.com/de/lesson/1/) angefangen


(25.08.2025) **Zusammenfassung Strukturierte Daten**    
Datenstruktur: Objekt zur Speicherung und Organisation von Daten  
Strukturierte Daten: Grundform (Tabelle, Kette...)  
Einordnung: semi-strukturierte Daten haben kein Datenmodell aber eine gewisse Struktur (z.m.B Mail)
Unstrukturierte Daten 

   
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
