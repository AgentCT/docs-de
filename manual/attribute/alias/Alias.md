# Das Attribut „Alias“

**Kurzbeschreibung:**

Alias-Feld z.B. für URLs  der Alias kann als Kombination von verschiedenen (vorhandenen) Attributen erstellt werden; als Option kann die Neuerstellung des Alias bei Änderungen der Ursprungs-Attribute erzwungen werden (Neuerstellung des Alias erzwingen); ein Alias wird nicht automatisch als eindeutiger Wert erstellt - dafür ist eine Aktivierung der Checkbox „Eindeutige Werte“ notwendig 

Im Auswahlfenster des Attributs „Alias“ können folgende Einstellungen vorgenommen werden:

![alias_i.png](alias_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte
- Neuerstellung des Alias erzwingen.


**Anzeigeeinstellungen**

- Alias-Präfix
- Alias-Postfix
- Alias-Felder

Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![alias_ii.png](alias_ii.png)

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

![alias_iii.png](alias_iii.png)

- Varianten überschreiben <br/>
  Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.

- Eindeutige Werte <br/>
  Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.

- Neuerstellung des Alias erzwingen. <br/>
  Auswählen, um eine Neuerstellung des Alias zu erzwingen, wenn sich eines der abhängigen Felder ändert. Beachten Sie, dass   bisherige URLs dadurch ungültig werden können.


Im Abschnitt **Anzeigeeinstellungen** des Attributes können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden:

![alias_iv.png](alias_iv.png)

- Alias-Präfix <br/>
  Optionale Angabe eines Präfix für die Erstellung des Alias.

- Alias-Postfix <br/>
  Optionale Angabe eines Postfix für die Erstellung des Alias.

- Alias-Felder <br/>
  Auswählen, um eine Neuerstellung des Alias zu erzwingen, wenn sich eines der abhängigen Felder ändert. Beachten Sie, dass               bisherige URLs dadurch ungültig werden können.


## Die Rendering-Einstellungen

![alias_v.png](alias_v.png)

Im Auswahlfenster für das Rendering können folgende Einstellungen vorgenommen werden:

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Alias"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_alias" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige Alias-Attribut eine eigene CSS-Klasse festegelegt werden.

## Die Eingabemaske

Im Auswahlfenster für die Eingabemaske können folgende Einstellungen vorgenommen werden:

![alias_vi.png](alias_vi.png)




**Typ**

![alias_vii.png](alias_vii.png)

- Typ
Wählen Sie den Attributstypen aus.

- Alias
Attribut, auf das sich diese Einstellung bezieht.




**Funktionsbezogene Einstellungen**

![alias_viii.png](alias_viii.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist. 

- Immer Speichern
Falls angewählt, wird dieses Feld - unabhängig davon, ob sich sein Wert geändert hat - immer gespeichert, 



**Anzeigeoptionen des Widgets**

![alias_ix.png](alias_ix.png)

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

**long (long)**

Sorgt dafür, dass das Eingabefeld zwei Spalten umfasst.

**wizard (wizard)**

Verkürzt das Eingabefeld, damit genug Platz für den Wizard (z.B. einen Date Picker) ist.

**m12 (m12)**

Fügt dem Element einen oberen Abstand von 12 Pixeln hinzu (z.B. für einzelne Checkboxen).







**Auflistung, Filterung und Sortierung im Backend**

![alias_x.png](alias_x.png)

- Filterbar
Auswählen, falls dieses Attribut für die Filterung im Backend zur Verfügung stehen soll.

- Suchbar
Auswählen, falls dieses Attribut für die Suche im Backend zur Verfügung stehen soll.


