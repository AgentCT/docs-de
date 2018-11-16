# Das Attribut: „Datei“

**Kurzbeschreibung:**





Im Auswahlfenster des Attributs „Datei“ können folgende Einstellungen vorgenommen werden:

![datei_i.png](datei_i.png)

**Typ, Benennung und Grundeinstellungen des Attributes**

- Attribut-Typ
- Spaltenname
- Name
- Beschreibung


**Erweiterte Einstellungen**

- Varianten überschreiben
- Eindeutige Werte
- Passen Sie den Dateibaum an
- Mehrfachauswahl


Im Abschnitt **Typ, Benennung und Grundeinstellungen des Attributes** können, wie bereits oben erwähnt verschiedene Einstellungen vorgenommen werden

![datei_ii.png](datei_ii.png)


- Attribut-Typ<br/>
Hier wurde der Attribut-Typ „URL“ ausgewählt. Bei der Auswahl eines anderen Attribut-Typs verändern sich die möglichen Einstellungen.

- Spaltenname<br/>
Der Spaltenname sollte möglichst eindeutig gewählt werden. Auf Sonderzeichen sollte unbedingt verzichtet werden. Der Spaltennamen entspricht dem späteren Namen unter dem die Informationen in der Datenbank gespeichert werden.

- Name<br/>
Der Name wird im Backend als auch im Frontend angezeigt. Die Anzeige des Namens kann im Frontend abgeschaltet werden. (siehe hierzu ….)

- Beschreibung<br/>
Im Feld Beschreibung kann eine längere Erklärung zum Feld eingegeben werden. Die Beschreibung wird im Backend gekürzt angezeigt, erst wenn mit der Maus über den Beschreibungstext gefahren wird, wird der vollständige Text angezeigt.
Der Beschreibungstext sorgt das eine Barrierefreiheit erreicht wird.

Im Abschnitt **Erweiterte Einstellungen des Attributes** können, wie bereit oben erwähnt verschiedene Einstellungen vorgenommen werden.

![datei_iii.png](datei_iii.png)

- Varianten überschreiben<br/>
Anwählen, falls Sie innerhalb des MetaModels Varianten wünschen um Elternwerte zu überschreiben.

- Eindeutige Werte<br/>
Wählen Sie diese Option, wenn Sie sicherstellen möchten dass jeder Wert nur einmal vorkommen kann.

- Passen Sie den Dateibaum an
Erlaubt Ihnen, individuelle Optionen für den Dateibaum zu setzen.

- Mehrfachauswahl
Wenn aktiviert können mehrere Dateien ausgewählt werden.

<br/>
<br/>

## Die Rendering-Einstellungen

![datei_iv.png](datei_iv.png)

Im Auswahlfenster für das Rendering können folgende Einstellungen vorgenommen werden:

**Typ**

![datei_v.png](datei_v.png)

- Attribut <br/>
  Hier das jeweilige Attribut ausgewählt. In diesem Fall wäre dies das Attribut "Alias"

- Angepasstes Template für die Ausgabe <br/>
  Als Standard ist das Template "mm_attr_datei" ausgewählt.

- Eigene CSS-Klasse <br/>
  Hier kann für das jeweilige Alias-Attribut eine eigene CSS-Klasse festegelegt werden


**Erweitern**

![datei_vi.png](datei_vi.png)

- Sortierung nach
Dateiname (aufsteigend)
Dateiname (absteigend)
Datum (aufsteigend)
Datum (absteigend)
Meta-Datei (meta.txt)
Zufällige Reihenfolge

Bitte wählen Sie die Sortierreihenfolge.

- Link als Download oder Lightbox erstellen
Das Item wird in einen Link eingebettet, der entweder für eine Großansicht oder einen Download dienen kann.


- Als Bildfeld mit Vorschaubild benutzen
Falls aktiviert wird für das Bild ein verkleinertes Vorschaubild generiert.


## Die Einstellungen in der Eingabemaske

![datei_vii.png](datei_viii.png)

**Typ**

![datei_viii.png](datei_viii.png)

- Typ
Wählen Sie den Attributstypen aus.

- Attribute
Attribut, auf das sich diese Einstellung bezieht.


**Funktionsbezogene Einstellungen**

![datei_ix.png](datei_ix.png)

- Nur lesen
Wenn aktiviert, erlaubt das Feld nur das Lesen und kann nicht geändert werden.

- Pflichtfeld
Wählen Sie diese Option, wenn das Attribut ein Pflichtfeld ist.

**Anzeigeoptionen des Widgets**

![datei_x.png](datei_x.png)

- Backend Klasse

Hier können Sie eine oder mehrere Backend-Klassen festlegen. Benutzen Sie den Stylepicker für eine einfachere Auswahl der Backend-Klassen.

Folgende Einstellungen sind möglich:

![datei_xi.png](datei_xi.png)

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

