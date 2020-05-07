## Aufgabenstellung 

Wir bitten Sie nun, ein Analyse-Plugin für ein solches hypothetishces System zu erstellen. Das Plugin soll eine Abschätzung des investierten Arbeitsaufwands innerhalb studentischer Projektgruppen anhand von Daten aus dem Github-Repository erlauben.

An das Plugin sind folgende Anforderungen zu stellen:

- Visualisierung des täglichen Aufwands (y-Achse) nach StudentIn über Zeit (x-Achse) in einem Graphen
  - Ein Trace pro StudentIn
  - Ein weiterer Trace mit Gruppendurchschnitt
  - Ein Trace mit dem Durchschnitt über alle Gruppen im Kurs
  
- Der Aufwand wird, je nach Einstellung, an der Zahl der Commits, oder geänderter Zeilen bemessen

- Im Repository gesetzte Milestones, sowie von Dozierenden gesetzte Deadlines sollen als vertikale, benannte Balken gerendert werden

- Als horizontale Balken sollen die zu der Zeit bearbeiteten Arbeitspakete (als Issues modelliert) angezeigt werden (Balken zwischen Start- und Enddatum, benannt mit Titel des Issues).  

Im folgenden ist eine beispielhafte Darstellung der Visualisierung abgebildet:

<p align="center">
  <img src="newplot.png" />
</p>

Bei der Implementierung
- sind Sie an keine konkrete Programmiersprache gebunden
- dürfen Sie den bestehenden Objekten beliebige Attribute ergänzen
- dürfen Sie fiktive Hilfsfunktionen benutzen - bitte benennen Sie diese verständlich

[Weiter zum Starterprojekt (Bitte in neuem Tab öffnen)](https://www.codepile.net/pile/pR3jy6rk)
