# Das Attribut „Checkbox“

**Kurzbeschreibung:**  <br/>
Kontrollkästchen (Checkbox): einzelne Checkbox für Boolsche-Werte mit der Checkbox können Boolsche-Werte (0|1) gesetzt werden; eine spezielle Variante ist das „Veröffentlichen“ - damit erscheint im Backend das Icon „Auge“ wobei die Filterung für die Veröffentlichung selbst erstellt werden muss; als Spaltenname für den Wert Veröffenlichung wird allgemein „published“ verwendet; über die Option „Listview checkbox“ kann ein eigenes Icon im Backend zur Anzeige des Status Verwendung finden

Im Auswahlfenster des Attributs „Checkbox“ können folgende Einstellungen vorgenommen werden:

![checkbox_i.png](checkbox_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte
- Veröffentlichen


**Anzeigeeinstellungen**

- Invertierte Anzeigeoption
- Listenanzeige-Checkbox


Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![checkbox_ii.png](checkbox_ii.png)

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

![checkbox_iii.png](checkbox_iii.png)

- Varianten überschreiben <br/>
  Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.

- Eindeutige Werte <br/>
  Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.

- Veröffentlichen
Falls aktiviert, werden die Datensätze im Frontend angezeigt. Gleichzeitig ist in der Backend-Ansicht das Symbol 'Auge' verfügbar, mit dem die Veröffentlichung eines Datensatzes ebenfalls gesteuert werden kann.

- Invertierte Anzeigeoption
Ist diese Option gesetzt, wird der Status "Veröffentlichen" invertiert (umgekehrt), d.h. das Element wird nicht angezeigt wenn diese Option gesetzt wird (Analog der Einstellung "Unsichtbar" bei den Contao-Inhaltselementen).

- Listenanzeige-Checkbox 
Ist diese Option gesetzt, wird ein zusätzliches Icon in der Listenanzeige des Backends eingefügt.


## Die Rendering-Einstellungen

![checkbox_iv.png](checkbox_iv.png)

Im Auswahlfenster für das Rendering können folgende Einstellungen vorgenommen werden:

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Alias"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_checkbox" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige Alias-Attribut eine eigene CSS-Klasse festegelegt werden.


## Die Eingabemaske

Im Auswahlfenster für die Eingabemaske können folgende Einstellungen vorgenommen werden:

![checkbox_v.png](checkbox_v.png)

**Typ**

![checkbox_vi.png](checkbox_vi.png)

- Typ
Wählen Sie den Attributstypen aus.

- Attribute
Attribut, auf das sich diese Einstellung bezieht.




**Funktionsbezogene Einstellungen**

![checkbox_vii.png](checkbox_vii.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist. 

- Abesenden bei Änderungen
Wenn aktiv, wird das Formular bei Änderungen eines Feldwertes abgesendet.


**Anzeigeoptionen des Widgets**

![checkbox_viii.png](checkbox_viii.png)

- Backend Klasse
Hier können Sie eine oder mehrere Backend-Klassen festlegen. Benutzen Sie den Stylepicker für eine einfachere Auswahl der Backend-Klassen.

![checkbox_ix.png](checkbox_ix.png)


Folgende Einstellungen sind möglich:

**w50 (w50)**

Setzt die Feldbreite auf 50% und floatet das Element (float:left).

**w50x (w50x)**

Entfernt die Voreinstellung für eine feste Höhe. Bitte gemeinsam mit mit "w50" verwenden.

**clr (clr)**

Hebt alle Floats auf.

**clx (clx)**

Entfernt die Voreinstellung "overflow:hidden". Bitte gemeinsam mit mit "clr" verwenden.

**long (long)**

Sorgt dafür, dass das Eingabefeld zwei Spalten umfasst.

**wizard (wizard)**

Verkürzt das Eingabefeld, damit genug Platz für den Wizard (z.B. einen Date Picker) ist.

**m12 (m12)**

Fügt dem Element einen oberen Abstand von 12 Pixeln hinzu (z.B. für einzelne Checkboxen).


**Auflistung, Filterung und Sortierung im Backend**

![checkbox_x.png](checkbox_x.png)

- Filterbar
Auswählen, falls dieses Attribut für die Filterung im Backend zur Verfügung stehen soll.
