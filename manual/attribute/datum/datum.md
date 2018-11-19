# Das Attribut „Datum“

**Kurzbeschreibung:**

Datum bzw. Datum und Uhrzeit die Daten werden als Unix-Timestamp gespeichert; bei eigenen SQL-Filterungen müssen ggf. Konvertierungen vorgenommen werden.

Im Auswahlfenster des Attributs „Land“ können folgende Einstellungen vorgenommen werden:

![datum_i.png](datum_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte


**Datum und Uhrzeit**

- Schema


Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![datum_ii.png](datum_ii.png)

- Attribut-Typ <br/>
Hier wurde der Attribut-Typ „Land“ ausgewählt. Bei der Auswahl eines anderen Attribut-Typs verändern sich die möglichen Einstellungen.

- Spaltenname <br/>
Der Spaltenname sollte möglichst eindeutig gewählt werden. Auf Sonderzeichen sollte unbedingt verzichtet werden. Der Spaltennamen entspricht dem späteren Namen unter dem die Informationen in der Datenbank gespeichert werden.

- Name <br/>
Der Name wird im Backend als auch im Frontend angezeigt. Die Anzeige des Namens kann im Frontend abgeschaltet werden. (siehe hierzu ....)

- Beschreibung <br/>
Im Feld Beschreibung kann eine längere Erklärung zum Feld eingegeben werden. Die Beschreibung wird im Backend gekürzt angezeigt, erst wenn mit der Maus über den Beschreibungstext gefahren wird, wird der vollständige Text angezeigt.
Der Beschreibungstext sorgt das eine Barrierefreiheit erreicht wird.

Im Abschnitt **Erweiterte Einstellungen** des Attributes können, wie bereit oben erwähnt verschiedene Einstellungen vorgenommen werden.

![datum_iii.png](datum_iii.png)

- Varianten überschreiben <br/>
  Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.

- Eindeutige Werte <br/>
  Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.


Im Abschnitt **Datum und Uhrzeit** des Attributes können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden:

![datum_iv.png](datum_iv.png)

- Schema <br/>
	- Uhrzeit
	- Datum
	- Datum und Uhrzeit


## Die Rendering-Einstellungen

![datum_v.png](datum_v.png)

Im Auswahlfenster für das Rendering können folgende Einstellungen vorgenommen werden:


**Typ**

![datum_vi.png](datum_vi.png)

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Alias"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_timestamp" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige Alias-Attribut eine eigene CSS-Klasse festegelegt werden.


**Datums- und Zeiteinstellungen**

![datum_vii.png](datum_vii.png)

- Fornat <br/>
Hier können Sie ein angepasstes Datumsformat festlegen, Falls Sie dieses Feld leer lassen wird der für das System festgelegte Standardwert benutzt. Der Formatstring wird mit der date()-Funktion von PHP erzeugt.


## Die Eingabemaske

Im Auswahlfenster für die Eingabemaske können folgende Einstellungen vorgenommen werden:

![datum_viii.png](datum_viii.png)

**Typ**

![datum_ix.png](datum_ix.png)

- Typ
Wählen Sie den Attributstypen aus.

- Attribute
Attribut, auf das sich diese Einstellung bezieht.


**Funktionsbezogene Einstellungen**

![datum_x.png](datum_x.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist. 


**Anzeigeoptionen des Widgets**

![datum_xi.png](datum_xi.png)

- Backend Klasse
Hier können Sie eine oder mehrere Backend-Klassen festlegen. Benutzen Sie den Stylepicker für eine einfachere Auswahl der Backend-Klassen.

![datum_xii.png](datum_xii.png)


Folgende Einstellungen sind möglich:

**w50 (w50)**

Setzt die Feldbreite auf 50% und floatet das Element (float:left).

 **w50x (w50x)**

Entfernt die Voreinstellung für eine feste Höhe. Bitte gemeinsam mit mit "w50" verwenden.

**clr (clr)**

Hebt alle Floats auf.

**clx (clx)**

Entfernt die Voreinstellung "overflow:hidden". Bitte gemeinsam mit mit "clr" verwenden.

**long (long)**# Das Attribut „Alias“



**Auflistung, Filterung und Sortierung im Backend**

![datum_xiii.png](datum_xiii.png)

- Filterbar
Auswählen, falls dieses Attribut für die Filterung im Backend zur Verfügung stehen soll.


- Suchbar
Auswählen, falls dieses Attribut für die Suche im Backend zur Verfügung stehen soll.