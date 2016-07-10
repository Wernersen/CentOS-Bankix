# CentOS Bankix
CentOS Bankix soll ein Live-Linux für sicheres Online-Banking bereit stellen und versucht damit die Nachfolge von c't Bankix anzutreten.
Leider ist das Projekt c't Bankix eingestellt worden (link: http://heise.de/-284099), so dass eine Alternative geschaffen werden muss.

Dieses Repository soll zeigen, wie man mit möglichst wenig Handarbeit ein Live-Linux aufbaut, das folgende Eigenschaften hat:
- 1.) Kernel mit Patch, der Festplattenzugriffe unterbindet.
- 2.) Read-Only Betriebssystem (Linux).
- 3.) Schreibbares Home-Verzeichnis, um Benutzer-spezifische Dateien speichern zu können.

Wichtig ist auch, dass das Vertrauen in CentOS Bankix durch Transparenz möglichst hoch gehalten wird. Es sollen keine großen Binärdateien aus dubiosen Quellen verwendet werden, von denen der Benutzer nicht wissen kann, was darin passiert. Die Schritte für die Zusammenstellung des Systems sind nachvollziehbar auszuführen. Als weiche Ziele ergeben sich: 
- 1.) Verwendung eines weit verbreiteten und gut gepflegten Linux als Ausgangs-Distribution (CentOS).
- 2.) Nur geringe und nachvollziehbare Eingriffe in die Ausgangs-Distribution.
- 3.) Zusätzliche Software nur aus wohlbekannten Quellen.
