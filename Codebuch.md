# Codebuch Testat Teil 2: VfB-Organe #
Codebuch Stand 2021-02-24<br>
erstellt von Artur Stolinsky (as383@hdm-stuttgart.de)

## Inhalt

- edgelist_VfB.csv
- nodelist_VfB.csv
- Codebuch.md

## Ursprung und Datenerhebung

Dieses Repository ist Teil einer Prüfungsvorleistung für den Kurs 226305 an der Hochschule der Medien in Stuttgart. Gutachter ist Prof. Dr. Swaran Sandhu. Die Aufgabenstellung lautete wie folgt (Kopie aus https://e-learning.hdm-stuttgart.de/moodle/mod/assign/view.php?id=181693):

"Beim VfB tobt ein Machtkampf um das Präsidentenamt. Ihre Aufgabe ist es, eine Netzwerkanalyse der Mitglieder des Vorstands und des Aufsichtsrats durchzuführen. Dazu interessiert uns besonders, wer mit wem vernetzt ist." Teilaufgaben waren dem Moodle-Kurs und der beigefügten Markdown-Vorlage zu entnehmen.

Für die Datenerhebung wurden folgende Quellen verwendet:
- https://www.vfb.de/de/1893/club/vfb-ag/organe-der-vfb-ag/ (für die Mitglieder der VfB-Organe)
- https://www.vfb.de/de/1893/business/partner/ (für die Sponsoren)
- https://de.wikipedia.org/wiki/ (für Unternehmensrecherche)

# Nodes und dazugehörige Attribute

**id**

eindeutige Codierung des Knotens

**name**

Vollständiger Name des Knotens

**type**

Unterscheidung zwischen Person und Unternehmen

0 = Person<br>
1 = Unternehmen

**age**

Alter der Person in ganzen Zahlen. Unternehmen und Personen, bei denen das Alter nicht ermittelt werden konnte, bekommen den Wert N/A.

**function**

