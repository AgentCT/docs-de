# Das Attribut: „URL“

**Kurzbeschreibung:**
Im Feld URL können neben den Angaben in welcher Tabelle die Daten gespeichert werden vor allem Links zu internen als auch externen Internetseiten gesetzt werden. Optional kann der Titel entfernt werden.


Im Auswahlfenster des Attributs „URL“ können folgende Einstellungen vorgenommen werden:

![url_i.png](url_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte


**Anzeigeeinstellungen**

- Titel entfernen

Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![url_ii.png](url_ii.png)

- Attribut-Typ<br/>
Hier wurde der Attribut-Typ „URL“ ausgewählt. Bei der Auswahl eines anderen Attribut-Typs verändern sich die möglichen Einstellungen.<br/>

- Spaltenname<br/>
Der Spaltenname sollte möglichst eindeutig gewählt werden. Auf Sonderzeichen sollte unbedingt verzichtet werden. Der Spaltennamen entspricht dem späteren Namen unter dem die Informationen in der Datenbank gespeichert werden.<br/>

- Name<br/>
Der Name wird im Backend als auch im Frontend angezeigt. Die Anzeige des Namens kann im Frontend abgeschaltet werden. (siehe hierzu ....)<br/>

- Beschreibung<br/>
Im Feld Beschreibung kann eine längere Erklärung zum Feld eingegeben werden. Die Beschreibung wird im Backend gekürzt angezeigt, erst wenn mit der Maus über den Beschreibungstext gefahren wird, wird der vollständige Text angezeigt.
Der Beschreibungstext sorgt das eine Barrierefreiheit erreicht wird.

Im Abschnitt **Erweiterte Einstellungen des Attributes** können, wie bereit oben erwähnt verschiedene Einstellungen vorgenommen werden.

![url_iii.png](url_iii.png)

- Varianten überschreiben<br/>
Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.<br/>

- Eindeutige Werte<br/>
Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.<br/>


Im Abschnitt **Anzeigeeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![url_iv.png](url_iv.png)

- Titel entfernen<br/>
Wird diese Funktion aktiviert wird im Frontend der Titel der URL entfernt.<br/>

## Die Rendering-Einstellungen

![ur![url_v.png](url_v.png)


**Typ** <br/>

![ur![url_vi.png](url_vi.png)

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Alias"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_url" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige URL-Attribut eine eigene CSS-Klasse festegelegt werden.


**Erweitern**

![ur![url_vii.png](url_vii.png)

- Nicht in neuem Tab öffnen <br/>
Falls ausgewählt wird die URL nicht in einem neuen Browsertab geöffnet.


## Die Einstellungen in der Eingabemaske

**Typ**

![url_vi.png](url_vi.png)

- Typ
Wählen Sie den Attributstypen aus.

- Attribute
Attribut, auf das sich diese Einstellung bezieht.












**Funktionsbezogene Einstellungen**

![url_vii.png](url_vii.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtgfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist.


**Anzeigeoptionen des Widgets**

![url_xi.png](url_xi.png)

- Backend-Klasse
Hier können Sie eine oder mehrere Backend-Klassen festlegen. Benutzen Sie den Stylepicker für eine einfachere Auswahl der Backend-Klassen.

![url_xii.png](url_xii.png)

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




