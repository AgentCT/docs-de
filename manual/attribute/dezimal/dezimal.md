# Das Attribut „Dezimal“

**Kurzbeschreibung:** <br/>

Dezimal: Dezimalzahlen das Attribut ist zur Speicherung von Dezimalzahlen wie Geldbeträge einzusetzen; es gibt zwei Dezimalstellen.

Im Auswahlfenster des Attributs „Dezimal“ können folgende Einstellungen vorgenommen werden:

![dezimal_i.png](dezimal_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte


Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![dezimal_ii.png](dezimal_ii.png)

- Attribut-Typ <br/>
Hier wurde der Attribut-Typ „Dezimal“ ausgewählt. Bei der Auswahl eines anderen Attribut-Typs verändern sich die möglichen Einstellungen.

- Spaltenname <br/>
Der Spaltenname sollte möglichst eindeutig gewählt werden. Auf Sonderzeichen sollte unbedingt verzichtet werden. Der Spaltennamen entspricht dem späteren Namen unter dem die Informationen in der Datenbank gespeichert werden.

- Name <br/>
Der Name wird im Backend als auch im Frontend angezeigt. Die Anzeige des Namens kann im Frontend abgeschaltet werden. (siehe hierzu ....)

- Beschreibung <br/>
Im Feld Beschreibung kann eine längere Erklärung zum Feld eingegeben werden. Die Beschreibung wird im Backend gekürzt angezeigt, erst wenn mit der Maus über den Beschreibungstext gefahren wird, wird der vollständige Text angezeigt.
Der Beschreibungstext sorgt das eine Barrierefreiheit erreicht wird.


Im Abschnitt **Erweiterte Einstellungen** des Attributes können, wie bereit oben erwähnt verschiedene Einstellungen vorgenommen werden.

![dezimal_iii.png](dezimal_iii.png)

- Varianten überschreiben <br/>
  Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.

- Eindeutige Werte <br/>
  Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.


## Die Rendering-Einstellungen

![dezimal_iv.png](dezimal_iv.png)

Im Auswahlfenster für das Rendering können folgende Einstellungen vorgenommen werden:

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Dezimal"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_decimal" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige Dezimal-Attribut eine eigene CSS-Klasse festegelegt werden.


## Die Eingabemaske

Im Auswahlfenster für die Eingabemaske können folgende Einstellungen vorgenommen werden:

![checkbox_v.png](dezimal_v.png)

**Typ**

![dezimal_vi.png](dezimal_vi.png)

- Typ
Wählen Sie den Attributstypen aus.

- Attribute
Attribut, auf das sich diese Einstellung bezieht.




**Funktionsbezogene Einstellungen**

![dezimal_vii.png](dezimal_vii.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist.


**Anzeigeoptionen des Widgets**

![dezimal_viii.png](dezimal_viii.png)

- Backend Klasse
Hier können Sie eine oder mehrere Backend-Klassen festlegen. Benutzen Sie den Stylepicker für eine einfachere Auswahl der Backend-Klassen.

![dezimal_ix.png](dezimal_ix.png)


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

![dezimal_x.png](dezimal_x.png)

- Filterbar
Auswählen, falls dieses Attribut für die Filterung im Backend zur Verfügung stehen soll.