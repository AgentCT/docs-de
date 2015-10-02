.. _ref_api_interf_attribute:

Attribute Interfaces
====================

.. warning:: Noch im Aufbau!

Die Attribute Interfaces erm�glichen den Zugriff auf die
Attribute - sprich die Spalten der MetaModel-Tabelle -
zum setzen, auslesen von Werten oder der Abfrage von
Informationen.


.. _ref_api_interf_attribute_iattributefactory:

IAttributeFactory Interface
...........................

Das IAttributeFactory Interface ist das "Factory Interface" zur Abfrage
eines Attributes.

Aktuelle Informationen unter: `IAttributeFactory <https://github.com/MetaModels/core/blob/master/src/MetaModels/Attribute/IAttributeFactory.php>`_

**Interfaces:**

``createAttribute($arrInformation, $objMetaModel)`` |br|
gibt die Attribut-Instanz f�r ein gegebenes MetaModel und einem Array an
Attributvorgaben zur�ck

``addTypeFactory(IAttributeTypeFactory $typeFactory)`` |br|
f�gt ein "typ factory" zum gegebenen "factory" hinzu

``getTypeFactory($typeFactory)`` |br|
gibt den "typ factory" zum gegebenen "factory" zur�ck

``attributeTypeMatchesFlags($factory, $flags)`` |br|
pr�ft das Attribute nach zu vergleichenden Flags

``getTypeNames($flags = false)`` |br|
gibt die registrierten Typennamen der Factory zur�ck

``collectAttributeInformation(IMetaModel $objMetaModel)`` |br|
gibt alle Attributinformationen eines MetaModel zur�ck

``createAttributesForMetaModel($metaModel)`` |br|
gibt alle Attributinstanzen eines MetaModel zur�ck

``getIconForType($type)`` |br|
gibt das Icon f�r ein gegebenen Typnamen zur�ck


.. _ref_api_interf_attribute_iattributefactory:

IAttribute Interface
....................

Das IAttribute Interface ist das grundlegende Interface f�r Attribute.

Aktuelle Informationen unter: `IAttributeFactory <https://github.com/MetaModels/core/blob/master/src/MetaModels/Attribute/IAttribute.php>`_

**Interfaces:**

``getName()`` |br|
gibt den (lesbaren) Namen oder Titel eines Attributes zur�ck

``getColName()`` |br|
gibt den Spaltennamen eines Attributes zur�ck

``getMetaModel()`` |br|
gibt die MetaModel-Instanz eines Attributes zur�ck

``get($strKey)`` |br|
gibt die Meta-Informationen eines Attributes zum gegebenen Schl�sselwert zur�ck

``set($strKey, $varValue)`` |br|
setzt die Meta-Informationen eines Attributes zum gegebenen Schl�sselwert

``handleMetaChange($strMetaName, $varNewValue)`` |br|
ersetzt die Meta-Informationen eines Attributes zum gegebenen Schl�sselwert

``initializeAUX()`` |br|
erstellt alle Hilfsdaten eines Attributes in anderen Tabellen 

``destroyAUX()`` |br|
l�scht alle Hilfsdaten eines Attributes in anderen Tabellen

``getAttributeSettingNames()`` |br|
gibt alle zul�ssigen Einstellungsnamen zur�ck

``getFieldDefinition($arrOverrides = array())`` |br|
gibt ein DCA wie "$GLOBALS['TL_DCA']['tablename']['fields']['attribute-name]"
zur�ck, mit einem optionalen Array mit zu �berschreibenden Parametern

``valueToWidget($varValue)`` |br|
gibt ein Widgetkompatiblen Wert eines nativen Attributwertes zur�ck

``widgetToValue($varValue, $intItemId)`` |br|
gibt ein Attributkompatiblen Wert eines nativen Widgetwertes zur�ck

``setDataFor($arrValues)`` |br|
speichert die Werte nach dem Schema "id => value" in der Datenbank

``getDefaultRenderSettings()`` |br|
gibt die Instanz der Standard-Rendereinstellungen des Attributes zur�ck

``parseValue($arrRowData, $strOutputFormat = 'text', $objSettings = null)`` |br|
gibt die konvertierten Daten bez�glich des gegebenen Ausgabeformates zur�ck

``getFilterUrlValue($varValue)`` |br|
gibt Attributwerte nach der Verwendung einer Filter-URL zur�ck

``sortIds($strListIds, $strDirection)`` |br|
gibt ein nach der Sortierrichtung ("ASC|DESC") soertieres Array an IDs zur�ck

``getFilterOptions($idList, $usedOnly, &$arrCount = null)`` |br|
gibt Attribute nach dem Schema "id => value" zur�ck

``searchFor($strPattern)`` |br|
gibt alle Items zu einem Suchmuster (z.B. Wildcard * oder ? f�r ein Buchtaben)
zur�ck

``filterGreaterThan($varValue, $blnInclusive = false)`` |br|
gibt eine Liste mit IDs von Items zur�ck, die gr��er als der gegebene Wert ist;
ist die Option "Inclusive" gesetzt, wird das Item bei Gleichheit mit in
die Liste aufgenommen

``filterLessThan($varValue, $blnInclusive = false)`` |br|
gibt eine Liste mit IDs von Items zur�ck, die kleiner als der gegebene Wert ist;
ist die Option "Inclusive" gesetzt, wird das Item bei Gleichheit mit in
die Liste aufgenommen

``filterNotEqual($varValue)`` |br|
gibt eine Liste mit IDs von Items zur�ck, die gleich als der gegebene Wert ist

``modelSaved($objItem)`` |br|
wird aufgerufen, wenn ein gegebenes Item gespeichert wird


.. _ref_api_interf_attribute_icomplex:

ISimple Interface
.................

Das ISimple Interface ist f�r alle "einfachen" Attribute gedacht,
die �ber die einfache Methode "SELECT colName FROM mm_table"
ermittelt werden k�nnen.

Aktuelle Informationen unter: `ISimple <https://github.com/MetaModels/core/blob/master/src/MetaModels/Attribute/ISimple.php>`_

**Interfaces:**

``getSQLDataType`` |br|
gibt die SQL-Typendeklaration wie z.B. "text NULL" zur�ck

``createColumn()`` |br|
erstellt die grundlegende Datenbankstruktur f�r ein gegbenenes Attribut

``deleteColumn()`` |br|
l�scht die grundlegende Datenbankstruktur f�r ein gegbenenes Attribut

``renameColumn($strNewColumnName)`` |br|
benennt die grundlegende Datenbankstruktur f�r ein gegbenenes Attribut um;
Achtung: die vorhandenen Daten in der Datenbank werden dabei gel�scht

``unserializeData($strValue)`` |br|
gibt die Rohdaten der Datenbank unserialisiert zur�ck

``serializeData($strValue)`` |br|
gibt die Daten serialisiert f�r die Datenbank zur�ck


.. _ref_api_interf_attribute_icomplex:

IComplex Interface
..................

Das IComplex Interface ist f�r alle "komplexen" Attribute gedacht,
die nicht �ber die einfache Methode "SELECT colName FROM mm_table"
ermittelt werden k�nnen.

Aktuelle Informationen unter: `IComplex <https://github.com/MetaModels/core/blob/master/src/MetaModels/Attribute/IComplex.php>`_

**Interfaces:**

``getDataFor($arrIds)`` |br|
gibt f�r die �bergebenen IDs die Werte als "id => 'native data'" zur�ck,
wobei "native data" sich nach dem jeweiligen Attributtyp richtet

``unsetDataFor($arrIds)`` |br|
l�scht die Werte der Attribute nach dem �bergebenen Array der IDs


.. _ref_api_interf_attribute_itranslated:

ITranslated Interface
.....................

Das ITranslated Interface ist f�r alle �bersetzten Attribute.

Aktuelle Informationen unter: `ITranslated <https://github.com/MetaModels/core/blob/master/src/MetaModels/Attribute/ITranslated.php>`_

**Interfaces:**

``searchForInLanguages($strPattern, $arrLanguages = array())`` |br|
gibt die IDs der Items zur�ck, welche mit der Angabe des Suchmusters (inkl. Wildcads)
und dem optionalen Array an Sprachen gefunden wurden

``setTranslatedDataFor($arrValues, $strLangCode)`` |br|
setzt den Wert f�r ein Item in der entsprechnden Sprache

``unsetValueFor($arrIds, $strLangCode)`` |br|
l�scht die Werte f�r das Array von Item-IDs in der entsprechnden Sprache

.. |br| raw:: html

   <br />
