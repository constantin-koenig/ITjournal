# Git Dokumentation

## D<small>as ist meine Git Dokumentation und gleichzeitig mein Wochenbericht der Woche 46</small>
!!! type note "Aber was ist Git eigentlich?" 

    Git ist eine freie Software zur Verteilung der Versionen und deren Verwaltung
    von Dateien. Diese Software stammt von dem berühmten Software Entwickler Linus Torvalds.

So funktioniert Git 
![alt text](https://github.com/constantin-koenig/ITjournal/blob/main/gitbuckets.jpeg?raw=true "So funktioniert Git")

## Auftrag

Während meiner HPC Zeit werde ich jeden Tages- und Wochenbericht auf meinem persönlichen Journal hochladen.
Dieses Journal bearbeite ich lokal, verwalte es mittels Git und veröffentliche es auf Github. 
Ich arbeite nun also täglich mit Git, deshalb schreibe ich diese Dokumentation.
Ich werde diese Dokumentation immer wieder verbessern.


## Anwendung

### add

Mit dem add Befehl fügt man Daten in die Staging Area. Dies ist also unser erster Schritt.

!!! example "Als Beispiel:"

    git add git.md


### commit

Als nächstes brauchen wir den commit Befehl. Mit diesem erstellen wir eine neue Änderung in unserem lokalen Repository.
Ausserdem können wir beim commit noch eine Notiz hinzufügen. Das erleichtert die Teamarbeit. 

!!! example "Als Beispiel:"
    git commit -m "Feature X verbessert"


### push

Zum Schluss laden wir unser lokales Repository auf den Server hoch. Das tun wir mit dem Befehl push. 

!!! example "Als Beispiel:"
    git push

