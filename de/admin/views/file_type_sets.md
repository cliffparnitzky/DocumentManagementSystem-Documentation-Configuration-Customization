# Dateityp-Sets

Hier erhalten Sie Informationen über die Ansicht für Dateityp-Sets.

**Seiteninhalt**

1. [Bezugsquellen](#bezugsquellen)
2. [Was sind Dateityp-Sets](#was-sind-dateityp-sets)
3. [Dateityp-Sets erstellen](#dateityp-sets-erstellen)
4. [Verarbeitung der Dateityp-Sets](#verarbeitung-der-dateityp-sets)

## Bezugsquellen

* **Datatyp-Sets** ist ein extra Add-On des ContaoDMS und muss separat installiert werden. 
* Sie können ContaoDMS auch als Bundle installieren. Darin ist das Add-On **Datatyp-Sets** dann schon enthalten 

### Quelle Add-On:
**Github:** https://github.com/ContaoDMS/dms-FileTypeSets  
**Packagist:** https://packagist.org/packages/contao-dms/file-type-sets

### Quelle Contao-dms/bundle-all:

**Github:** https://github.com/ContaoDMS/bundle-all  
**Packagist:** https://packagist.org/packages/contao-dms/bundle-all


## Was sind Dateityp-Sets

* Dateityp-Sets enthalten erlaubte Dateitypen die in eine Kategorie abgelegt werden dürfen.
* Ein Set muss mindestens einen erlaubten Dateityp enthalten.
* Die Sets stehen dann bei Neuanlage von Kategorien bzw. Anpassung von bestehenden Kategorien zur Verfügung und können leicht ausgewählt werden.
* Dateityp-Sets vereinfachen die Zuweisung erlaubter Dateitypen die in eine Kategorie abgelegt werden dürfen erheblich.


## Dateityp-Sets erstellen

→ im Modul DMS → Dateityp-Sets

![Backend Menü](backend_file_type_sets.png)

 → dann auf „Neues Dateityp-Set“

![Neues Dateityp-Sets anlegen](create_new_file_type_sets.png)

* **Name:** Aussagekräftigen Namen vergeben (z.B. Word Dokumente)
* **Beschreibung:** optionale Angabe einer Beschreibung
* **Erlaubte Dateitypen:** doc, docx (Gross oder Kleinschreibung spielt keine Rolle)

**Tip:** Sollen mehrere Dateitypen in einem Set enthalten sein, werden diese im Feld „Erlaubte Dateitypen“ durch Komma getrennt eingetragen. Z.B. pdf, zip oder jpg, gif, tif

* **Dateityp-Sets veröffentlichen:** Checkbox aktivieren

![Dateityp-Sets konfigurieren](file_type_sets_settings.png)

Jetzt hat man ein Dateityp-Set vom Typ **doc,docx** angelegt. 

Auf diese Weise können beliebig viele Sets angelegt werden.

**Note:** Sie brauchen  *.doc und *.docx oder *.xls und *xlsx Dateitypen nicht in ein Dateityp-Set packen, sondern können natürlich auch je ein Set erstellen. So kann man dafür sorgen, das z.B. in eine bestimmte Kategorie nur Dateien vom Typ *.docx (*.xlsx) und in einer anderen Kategorie nur *.doc (*.xls) abgelegt werden dürfen.

![Dateityp-Sets Liste](file_type_sets_list.png)


## Verarbeitung der Dateityp-Sets

Informationen wie sie **Dateityp-Sets** weiterverarbeiten, z.B. über die Vererbung, erhalten sie im Kapitel **Kategorien** unter dem Abschnitt [Kategorieeinstellungen erlaubte Dateitypen](categories.md#erlaubte-dateitypen)
