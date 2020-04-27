# Tools in der Softwaretechnikausbildung: Plugin-Challenge

Sehr geehrte Teilenhmende,

vielen Dank, dass Sie sich die Zeit nehmen, an dieser Vorstudie teilzunehmen. Im Rahmen meiner Masterarbeit entwickle ich eine erweiterbare Online-Plattform, die Lehrenden dabei helfen soll mittels automatisierter Analysen von ```github```-Repositories einen besseren Einblick in das Arbeitsverhalten ihrer Studierenden zu gewinnen.

Die Plattform soll es Nutzern erlauben Extraktion, Vor- und Aufbereitung dieser Daten über selbst erstellte Plugins an ihre eigenen Bedürfnisse anzupassen. Um die Anforderungen an die Formulierung eines Plugin-Systems besser zu verstehen, bitten wir Sie um die beispielhafte Entwicklung eines **Analyse-Plugins zum Vergleich des Arbeitsaufwands innerhalb einer Projektgruppe**. 

An das Plugin sind folgende Anforderungen zu stellen.

- Visualisierung des täglichen Aufwands (y-Achse) nach Autor über Zeit (x-Achse) in einem Graphen
  - Ein Trace pro StudentIn
  - Ein weiterer Trace mit Gruppendurchschnitt
  - Ein Trace mit dem Durchschnitt über alle Gruppen im Kurs
  
- Der Aufwand wird, je nach Konfiguration, an der Zahl der Commits, oder geänderter Zeilen bemessen

- Im Repository gesetzte Milestones, sowie von Dozierenden gesetzte Deadlines sollen als vertikale, benannte Balken gerendert werden

- Als horizontale Balken sollen die zu der Zeit bearbeiteten Arbeitspakete (als Issues modelliert) angezeigt werden (Balken zwischen Start- und Enddatum, benannt mit Titel des Issues).  

Implementieren Sie bitte die beschriebene Analyse in das Skelett der zu implementierenden Funktion. 
 - Sie dürfen InputData und Config nach Belieben Funktionen und Properties hinzufügen
 - Sie dürfen beliebige, imaginäre Utility- und Kumulationsfunktionen referenzieren (z.B. "sum", "avg"...)
 - Sie sind an KEINE KONKRETE PROGRAMMIERSPRACHE gebunden, können also alle favorisierte Paradigmen nutzen, die sich in einer objketorientierten Sprache umsetzen ließe. 
