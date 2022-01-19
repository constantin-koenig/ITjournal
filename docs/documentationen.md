# Meine Wocheberichte

### Wochenbericht der Woche 03

** Handlung **

In diesem Wochenbericht werde ich über folgende Dinge berichten.

- RPM
- Modularity

Beides habe ich zur Umsetzung des Webserver benutzt.

** Umsetzung **

Modularity ist mir beim PHP 8 begegnet. Da Rockylinux standard mässig kein PHP 8
 unterschtüzt, musste ich auf die Remi Repos ausweichen.
https://blog.remirepo.net/post/2020/11/30/Install-PHP-8.0-on-CentOS-RHEL-or-Fedora

Modularity bringt den Vorteil, dass man z.B. nun nicht mehr nur auf eine PHP Version angewiesen ist.
 Das bedeutet, dass ich sowohl PHP 8.0 als auch PHP 7.2 gleichzeitig installieren kann.
 Nun ist es also möglich, dass ich auf dem gleichen Webserver eine Seite mit PHP 8.0 und
 eine Seite mit PHP 7.2 laufen lassen kann.

RPM ** WB noch nicht fertig **

** Wie geht es weiter? **

** Was lief gut **

** Was lief schlecht **

---

### Wochenbericht der Woche 02

** Handlung **

Diese Woche habe ich den Web Server aufgesetzt.
Dabei musste ich folgende Sachen installieren:

- PHP 8
- Apache

Dem Webserver wird dann nächste Woche noch Wordpress hinzugefügt.

** Umsetzung **

Zuerst habe ich Apache installiert. Dies lief sehr gut und konnte ich
 einfach und selbständig mit einem Tutorial aus dem Internet bewältigen.
Danach habe ich PHP 8 installiert. Das war eher schwierig (Stichwort Modularity).
Deshalb habe ich PHP 8 von deinem Git Repo genommen, welches extra für Rocky Linux
 und andere Distributionen erstellt wurde. Mit diesem konnte man dann PHP 8 installieren.
Also habe ich diese mit Hilfe eines online Tutorials installiert.

** Wie geht es weiter? **
Nun werde ich all diese Befehle noch in ein Skript schreiben, so dass man den Webserver
 immer wieder in kürzester Zeit hochziehen kann.

** Was lief gut **

Die Installation lief eigentlich bei beiden Programmen sehr gut und hat mir auch spass gemacht.
Ich denke der Webserver wird mir allgemein viel spass bereiten, da ich gerade das Arbeiten mit
 Wordpress und HTML echt cool finde!

** Was lief schlecht **

Das Arbeiten am Webserver lief sehr schnell und flüssig, jedoch habe ich letzte Woche durch die
 Präsentation und dem Wiedereinstieg ein bisschen Zeit verloren.

---

### Wochenbericht der Woche 48

** Handlung **

Diese Woche habe ich mit Vagrant gearbeitet.
Ich habe bereits in meiner SYS Zeit schon mit Vagrant gearbeitet.
Nun habe ich diese Woche von Michael den Auftrag bekommen, eine virtuelle Umgebung mit Vagrant zu erstellen.
Die Umgebung sollte folgendes beinhalten:

- Datenbank Server
- Webserver

Der Webserver soll die angeforderten Daten vom Datenbankserver beziehen.  
Ausserdem soll auf dem Webserver WordPress installiert und benutzt werden.
Der Datenbankserver verwendet MariaDB als Datenbank.

** Umsetzung **

Am Ersten Tag habe ich mich nochmals mit Vagrant und dem Vagrant File vertraut gemacht.
Am Zweiten Tag habe ich es dann geschafft, dass beide Server von einem Vagrantfile aus verwaltet werden.
Zuletzt habe ich dann einen weiteren Netzwerkadapter zu den beiden VMs hinzugefügt, so dass diese miteinander kommunizieren können.

** Wie geht es weiter? **

In der Woche 49 werde ich mit dem Projekt weiterfahren.

## Wochenbericht der Woche 47

** Tätigkeit **

Am Montag bin ich mit Michael den Serverraum im Von Roll anschauen gegangen.
Dort haben wir einen Server neu verkabelt und einen RAM-Riegel aus einem Server ausgetauscht.

Michael hat mir ebenfalls einiges dazu erklärt, welcher Server für welchen Dienst zuständig ist.
Zudem erklärte er mir, welche Komponenten in welchem Server verbaut sind und warum diese das benötigen.
Kurz hat er mir auch einige Sachen zur Infrastruktur erklärt, z.B. die Stromversorgung, oder die Wasserkühlung.

** Kompetenzen **

- Selbstkompetenz:
In dieser Angelegenheit war ich nicht die grösste Hilfe, da ich bisher noch nicht so viel Erfahrung mit dem technischen Verwalten der Server sammeln konnte. Nun konnte ich Michael doch teilweise mit dem Verkabeln helfen. Die Arbeit hat mir aber sehr Spass gemacht, vielleicht wäre die Serververwaltung eine Fachrichtung, welche ich mir für meine Zukunft vorstellen könnte.

- Sozialkompetenz:
Ich habe mit Michael zusammen gearbeitet und ihm aufmerksam zugehört. Die Server, die nah am Boden waren, habe ich verkabelt, während Michael die Kabel oben am Switch verkabelt hat. So haben wir uns gemeinsam organisiert.
