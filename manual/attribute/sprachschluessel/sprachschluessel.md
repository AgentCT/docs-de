# Das Attribut „Sprachschlüssel“

**Kurzbeschreibung:**

Auswahl von ISO-Sprachcodes mit dem Attribut steht eine Auswahl von Sprachcodes zur Verfügung; die Sprachcodes können per Checkbox ausgewählt werden. Im Auswahlfenster des Attributs „Alias“ können folgende Einstellungen vorgenommen werden:

![sprachschluessel_i.png](sprachschluessel_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte


**Anzeigeeinstellungen**

- Sprachschlüssel

Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![sprachschluessel_ii.png](sprachschluessel_ii.png)

- Attribut-Typ <br/>
Hier wurde der Attribut-Typ „Alias“ ausgewählt. Bei der Auswahl eines anderen Attribut-Typs verändern sich die möglichen Einstellungen.

- Spaltenname <br/>
Der Spaltenname sollte möglichst eindeutig gewählt werden. Auf Sonderzeichen sollte unbedingt verzichtet werden. Der Spaltennamen entspricht dem späteren Namen unter dem die Informationen in der Datenbank gespeichert werden.

- Name <br/>
Der Name wird im Backend als auch im Frontend angezeigt. Die Anzeige des Namens kann im Frontend abgeschaltet werden. (siehe hierzu ....)

- Beschreibung <br/>
Im Feld Beschreibung kann eine längere Erklärung zum Feld eingegeben werden. Die Beschreibung wird im Backend gekürzt angezeigt, erst wenn mit der Maus über den Beschreibungstext gefahren wird, wird der vollständige Text angezeigt.
Der Beschreibungstext sorgt das eine Barrierefreiheit erreicht wird.

Im Abschnitt **Erweiterte Einstellungen** des Attributes können, wie bereit oben erwähnt verschiedene Einstellungen vorgenommen werden.

![sprachschluessel_iii.png](sprachschluessel_iii.png)

- Varianten überschreiben <br/>
  Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.

- Eindeutige Werte <br/>
  Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.


Im Abschnitt **Anzeigeeinstellungen** des Attributes können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden:

![sprachschluessel_iv.png](sprachschluessel_iv.png)

- Sprachschlüssel <br/>



## Die Rendering-Einstellungen

![sprachschluessel_v.png](sprachschluessel_v.png)

Im Auswahlfenster für das Rendering können folgende Einstellungen vorgenommen werden:

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Alias"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_langcode" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige Alias-Attribut eine eigene CSS-Klasse festegelegt werden.


## Die Eingabemaske

Im Auswahlfenster für die Eingabemaske können folgende Einstellungen vorgenommen werden:

![sprachschluessel_vi.png](sprachschluessel_vi.png)

**Typ**

![sprachschluessel_vii.png](sprachschluessel_vii.png)

- Typ
Wählen Sie den Attributstypen aus.

- Attribute
Attribut, auf das sich diese Einstellung bezieht.




**Funktionsbezogene Einstellungen**

![sprachschluessel_viii.png](sprachschluessel_viii.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist. 

- Leere Option einfügen
Falls diese Option angewählt ist, wird zusätzlich "kein Element ausgewählt" ermöglicht.


**Anzeigeoptionen des Widgets**

![sprachschluessel_ix.png](sprachschluessel_ix.png)

- Backend Klasse
Hier können Sie eine oder mehrere Backend-Klassen festlegen. Benutzen Sie den Stylepicker für eine einfachere Auswahl der Backend-Klassen.

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

![sprachschluessel_x.png](sprachschluessel_x.png)

- Filterbar
Auswählen, falls dieses Attribut für die Filterung im Backend zur Verfügung stehen soll.g](alias_i.png)


- Suchbar
Auswählen, falls dieses Attribut für die Suche im Backend zur Verfügung stehen soll.