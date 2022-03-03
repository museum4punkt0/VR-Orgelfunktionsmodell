# VR-Orgelfunktionsmodell

## Inhaltsverzeichnis
-	Beschreibung
-	Kurzbeschreibung
-	Entstehungskontext
-	Förderung
-	Bedienung der Sprachauswahl
-	Möglichkeiten in der Anwendung
-	Credit
-	Lizenz

## Beschreibung
Die Appliaktion „VR-Orgel“ ist eine VR-Software, die dem Museumbesucher die Funktionsweise einer Orgel näher bringen soll. So haben Nutzer während ihrer Erfahrung in der virtuellen Realität, die Möglichkeit die Orgel zu spielen und die Töne mit Hilfe der Registerzüge zu beeinflussen. Eine weitere Möglichkeit ist die Orgel in ihre Einzelteile zu zerlegen und sich jegliche Teile genauer anzuschauen. Zudem haben die Intressenten, durch verschiedene Werkzeuge und Buttons die Möglichkeit den Blasebalg aufzuziehen und durch einen Klick auf den Button der Luftsimulation, die Möglichkeit dem Verlauf des Windes, welcher im Blasebalg beginnt und in der Verwirbelung der Pfeifen endet, nachzuvollziehen. Weitere Button, die dem Nutzer zur Verfügung stehen ist der Button des Gitternetz, das die gesamte Orgel als Wireframe darstellen lässt und die Stellen an denen man sich mit der VR-Brille/Kopf nähert genauer erscheinen. Der dritte und letzte Button ermöglicht dem Nutzer die Orgel in den Ausgangszustand zurück zu setzen. Neben den Button gibt es auch zwei Werkzeuge, die benutzt werden können. Ein Werkzeug ist die Lupe, diese kann der Nutzer auf einzelne Teile richten und eine Audiospur wird abgespielt, diese erklärt die Funktionsweise der einzelnen Bereiche. Bei dem zweiten Werkzeug handelt es sich um eine Schere, dies ermöglicht den Nutzer die Orgel nach belieben auseinander zu schneiden und sich das Innenleben des Musikinstruments genauer anzusehen. 
Die Software wurde mit der Unreal Engine erstellt und kann mit VR-Setup verbunden werden.  Die Entwicklung der Applikation wurde in Zusammenarbeit mit der Ludwig-Maximilians Universität und dem Deutschen Museums München im Rahmen des Kurses „PEM-Entwicklung von Mediensystemen“ und eines Einzelpraktikums begonnen und weitergeführt. Beendet wurde das Projekt in persönlicher Zusammenarbeit.

## Kurzbeschreibung
„VR-Orgelfunktionsmodell“ ist eine VR-Software, die dem Nutzer ein umfassendes Erlebnis zur Erkundung einer Orgel auf verschiedenen Ebenen bietet. Die Applikation wurde mit der Unreal Engine im Rahmen einer Zusammenarbeit mit dem Deutschen Museum erstellt. 

## Entstehungskontext und Förderung
Die Idee für die Software entstand im Rahmen der Zusammenarbeit des Deutschen Museums in München und der Ludwig-Maximilians Universität (LMU) für den Kurs „PEM – Entwicklung von Mediensystemen“. Nach Beendigung dieses Kurses wurde die Entwicklung an der Software in Form eines Einzelpraktikums an der LMU in enger Zusammenarbeit des Deutschen Museums weitergeführt. Am Ende dieses Einzelpraktikums war das Ergebnis eine funktionierende, aber noch ausbaufähige Software. Diese Software ist entstanden im Verbundprojekt museum4punkt0 – Digitale Strategien für das Museum der Zukunft, Teilprojekt 3D-Visualisierung: Perspektiven in der musealen Vermittlung. Das Projekt museum4punkt0 wird gefördert durch die Beauftragte der Bundesregierung für Kultur und Medien aufgrund eines Beschlusses des Deutschen Bundestages. Weitere Informationen: www.museum4punkt0.de

## Installation und Inbetriebnahme

Die Anwendung wurde mit /hier die Unitiy Version/ erstellt.

### Minimale Systemvoraussetzungen für die Entwicklung

### Minimale Systemvoraussetzungen für die Inbetriebnahme

Um die Anwendung zu bearbeiten kann der Inhalt, der über den folgenden Link zum Download bereit steht, in ein neues Projekt gezogen werden oder die .unitypackages-Dateien in ein Unity-Projekt importiert werden: (Quelle: https://dam.museum4punkt0.de/?r=1369&k=7ebbac39d6)



### Bedienung der Sprachauswahl
Beim Einfügen neuer Sprachen in die vorbereitete Sprachauswahl müssen einige Dinge beachtet werden: innerhalb des Projektordners gibt es einen Ordner namens „Language“. In diesem Ordner befinden sich weitere Ordner, welche die jeweiligen Sprachen enthalten. Die Benennung dieser Ordner spielt keine Rolle. Es ist allerdings nicht möglich mehr als sechs Sprachen hinzuzufügen. Innerhalb der jeweiligen Sprachordner befindet sich eine txt-Datei. Die Bezeichnung dieser Datei („LangText.txt“) darf nicht geändert werden! Es enthält mehrere Codewörter, wie z.B. ToolMagGlass=Lupe. Der Begriff, welcher sich nach dem Gleichheitszeichen befinden, wird in das Spiel eingefügt (nach dem Gleichheitszeichen kein Leerzeichen!). Neben dieser Datei, befinden sich im Sprachenordner die jeweiligen Dateien der gesprochenen Sprachen. Dabei handelt es sich um .wav-Formate. Es kann nur dieses Format verwendet werden. Alle Dateien in den jeweiligen Ordnern müssen exakt den selben Dateinamen haben, wie in der deutschen Fassung. Es darf sich hier lediglich der Inhalt ändern. Auch dürfen die Sprachordner nur genau die genannten Dateien enthalten, da genau diese eingelesen werden (10 Sprachdateien, 1 Textdatei). 

### Möglichkeiten in der Anwendung

#### Teleportieren/Navigation
Um sich in der virtuellen Realität zu bewegen, wird die Teleportation verwendet. Die Nutzenden haben die Möglichkeit sich in einem festgelegten Navigationsbereich zu bewegen, allerdings sind zudem feste Teleportationspunkte ausgewählt, um es Anfänger/innen zu erleichtern sich im Raum zu bewegen. 

#### Spielen der Orgel
Nutzer/innen haben die Möglichkeit das Musikinstrument zu spielen. Dafür muss dieser die Tasten der Orgel drücken. Zudem ist es möglich verschiedene Registerzüge zu siehen und somit unterschiedliche Töne erzeugen. Die Aufnahmen der Töne wurden vor Ort im Deutschen Museum München am Orgelmodel aufgenommen und bearbeitet. 

#### Erforschung des Musikinstruments 
In der virtuellen Realität können die Anwender/innen das Musikinstrument erforschen, indem sie die Möglichkeit haben die Orgel auseinander zu bauen und jedes Bauteil individuell zu betrachten. Zudem können die Nutzer/innen den Blasebalg anhand eines Riemens aufziehen und mit Wind befüllen. 

#### Neustart
Am Rande des Musikinstruments befindet sich ein Button mit der Bezeichnung "Neustart", welche die Orgel auf den Ausgangszustand zurücksetzt.

#### Wireframe
Ein weiterer Button steht dem Anwendenden zur Verfügung. Nachdem dieser Button geklickt wurde, erscheint das Musikinstrument als Wireframe. Zusätzlich wird die Stelle des Wireframes deutlicher, welcher sich am nächstenn zum Kopf befindet. 

#### Luftsimulation 
Der letzte Button zeigt die Luftsimulation in der Orgel. Es simuliert wie der Wind, welcher sich zunächst im Blasebalg, durch das Aufziehen, sammelt. Danach weiter nach oben zieht und den Raum unter der Tontraktur fühlt und wie der Wind durch die Tontrakturen zieht, wenn die Orgel gespielt werden würde. Zum Ende hin wird der Wind in den Pfeifen verwirbelt und ein Ton entsteht. 

#### Werkzeuge
Neben den genannten Möglichkeiten das Musikinstrument zu erforschen, stehen dem Nutzenden zwei weitere Werkzeuge zu Verfügung:

LUPE: Hinter ausgewählten Bauteilen befinden sich hinterlegten Tonspuren. Durch die Überlagerung mit der Lupe, ertönen Beschreibungen der ausgewählten Bauteile. 

SCHERE: Die Schere bietet die Möglichkeit die Orgel zu durchschneiden und die Bauteile bis hin zum gesamten Musikinstrument von innen zu betrachten. 


## Credit
Auftraggeber: Deutsches Museum, München 
Umsetzung: Julius Girbing & Lisa-Marie Bauer

## Lizenz 
Copyright (c) 2020/2021, Deutsches Museum/museum4punkt0  & Julius Girbig, Lisa-Marie Bauer 

Hiermit wird jeder Person, die eine Kopie dieser Software und der zugehörigen Dokumentationsdateien (die "Software") erhält, kostenlos die Erlaubnis erteilt, uneingeschränkt mit der Software zu handeln, einschließlich und ohne Einschränkung der Rechte zur Nutzung, zum Kopieren, Modifizieren, Zusammenführen, Veröffentlichen, Verteilen, Unterlizenzieren und/oder Verkaufen von Kopien der Software, und Personen, denen die Software zur Verfügung gestellt wird, dies unter den Bedingungen der MIT-Lizenz zu gestatten: Näheres siehe hier in der [Lizenz Datei](docs/LICENSE.md).
