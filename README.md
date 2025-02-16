# Low-Cost 3D-Gebäudemodellierung: Ein Praxisbeispiel mit der DJI Mini 4K und Open-Source-Tools

## Einleitung

* **Zweck des Berichts:** Bericht so verfassen, dass er sowohl für Laien als auch für Fachleute verständlich ist. Lernprozess und die Möglichkeiten betone, die sich durch die Erstellung von 3D-Modellen mit Drohnen und Open-Source-Software ergeben.
* **Gebäudebeschreibung:** Neben den grundlegenden Informationen auch auf architektonische Besonderheiten des Gebäudes eingehen und ggf. historische Hintergründe recherchieren.
* **Drohne und Software:** Die technischen Daten der DJI Mini 4K und die wichtigsten Funktionen von WebODM/OpenDroneMap und FreeCAD kurz vorstellen.

Die Erstellung von 3D-Gebäudemodellen gewinnt in vielen Bereichen zunehmend an Bedeutung.  Anwendungen finden sich in der Architektur und Stadtplanung, im Facility Management, der Energieberatung,  bei der Dokumentation von Kulturgütern und in vielen weiteren Bereichen. Traditionell werden solche Modelle mit aufwendigen und teuren Verfahren wie Laserscanning erstellt.  Der Einsatz von Drohnen in Kombination mit  Open-Source-Software bietet eine kostengünstige und effiziente Alternative.

### Zweck des Berichts

Dieser Bericht dokumentiert die Erstellung eines 3D-Gebäudemodells mit Hilfe einer DJI Mini 4K Drohne und den Open-Source-Programmen WebODM/OpenDroneMap und FreeCAD. Ziel ist es, die Möglichkeiten und Herausforderungen dieser Methode aufzuzeigen und einen praxisnahen Einblick in den Workflow der  Low-Cost 3D-Gebäudemodellierung zu geben. Der Bericht richtet sich sowohl an  Einsteiger, die erste Erfahrungen mit der Drohnenphotogrammetrie sammeln möchten, als auch an Fachleute, die nach kostengünstigen Alternativen zu herkömmlichen Verfahren suchen. 

### Gebäudebeschreibung

Das für die Modellierung ausgewählte Gebäude ist "Im Gries" in Ramsen. Es handelt sich um ein Reihenhaus in Holzbauweise. Die einzelnen Reihenhäuser sind leicht versetzt zueinander gebaut, was dem Gebäudekomplex eine interessante Struktur verleiht. Das Gebäude eignet sich gut für die 3D-Modellierung mit einer Drohne.

### Drohne und Software

Für die Datenerfassung wurde eine DJI Mini 4K Drohne verwendet.  Diese Drohne zeichnet sich durch ihr geringes Gewicht,  ihre einfache Bedienung und ihre gute Bildqualität aus.  Sie ist daher ideal für die  kostengünstige 3D-Modellierung von Gebäuden geeignet.  

Die Verarbeitung der Drohnenbilder erfolgte mit der Open-Source-Software WebODM/OpenDroneMap.  Diese Software ermöglicht die Erstellung von  Orthofotos, Punktwolken und  digitalen Oberflächenmodellen (DSM) aus Luftbildern. Für die Modellierung des Gebäudes wurde die ebenfalls quelloffene Software FreeCAD verwendet. FreeCAD bietet umfangreiche Funktionen zur 3D-Modellierung und Konstruktion.

## Methodik

* **Planung:**  Hier detailliert auf die Flugplanung eingehen und die gewählten Parameter begründen. Auch die Anzahl und Position der GCPs beschreiben und erläutern, wie ich sie vermessen habe.
* **Datenerfassung:**  Wetterbedingungen während des Fluges dokumentieren und ggf. auf Besonderheiten hinweisen (z.B. Wind, Schattenwurf).
* **Bildverarbeitung:** Die einzelnen Schritte der Bildverarbeitung in WebODM/OpenDroneMap mit Screenshots veranschaulichen und die wichtigsten Parameter erläutern.
* **Modellierung:**  Den Import des DSM in FreeCAD beschreiben und die Werkzeuge und Funktionen vorstellen, die ich zur Modellierung verwendet habe.  Besonders die Herausforderungen bei der Modellierung komplexer Gebäudeteile hervorheben.

## Ergebnisse

* **Visualisierung:**  Das 3D-Modell aus verschiedenen Perspektiven präsentieren und ggf. ein Video erstellen, das einen virtuellen Rundflug um das Gebäude ermöglicht.
* **Genauigkeitsanalyse:**  Die Messungen und Tests durchführen und die Ergebnisse in Tabellen und Diagrammen darstellen.  Dabei auf die Ursachen für Abweichungen eingehen und die Grenzen der verwendeten Methode diskutieren.
* **CityGML-Konvertierung:** Prozess der CityGML-Konvertierung beschreiben und die Vorteile dieses Formats für die Nutzung in Geoinformationssystemen erläutern.

## Diskussion

* **Herausforderungen:**  Herausforderungen bei der Erstellung des Modells detailliert beschreiben und Lösungsansätze diskutieren.
* **Verbesserungspotenzial:** Konkrete Vorschläge für Verbesserungen machen, z.B. die Verwendung von mehr GCPs, die Optimierung der Flugplanung oder die Nutzung anderer Software.
* **Anwendungsgebiete:** Verschiedene Anwendungsgebiete für 3D-Gebäudemodelle aufzeigen, z.B. in der Architektur, Stadtplanung, Energieberatung oder im Katasterwesen.

## Schlussfolgerung

* **Zusammenfassung:** Die wichtigsten Ergebnisse und Erkenntnisse des Projekts zusammenfassen.
* **Ausblick:** Einen Ausblick auf mögliche zukünftige Entwicklungen geben, z.B. die Automatisierung der Modellierung oder die Integration von künstlicher Intelligenz.
