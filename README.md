M300 - LB1 Dokumentation
======

Dieses Repository behandelt die Installation von GitHub, VirtualBox, Vagrant und Visual Studio Code.

#### Einleitung

Die nachstehende Dokumentation wurde von Michael Blickenstorfer im Rahmen des Moduls M300 (Plattformübergreifende Dienste in ein Netzwerk integrieren)
erarbeitet und zeigt alle Schritte auf, die es zur Einrichtung einer vollständig funktionsfähigen Toolumgebung benötigt.

#### Revision History

| Datum         | Änderungen                                                | Kürzel  |
| ------------- |:-----------------------------------------------------------| -------:|
| 29.08.2018    | Erstellung der Datei & erste Änderungen eingeführt        |   MBL   |
| 08.09.2018    | Einleitung, Voraussetzungen, Inhaltsverzeichnis & Kapitel 1 erarbeitet                                    |   MBL   |
| zebra stripes | are neat                                                  |    $1   |

#### Voraussetzungen
* macOS High Sierra (Version 10.13.6)
* GitHub Account
* Git-OSX-Installer (Version 2.15.0)
* VirtualBox (Version 5.2.18)
* Vagrant (Version 2.1.4)
* Visual Studio Code (Version 1.26.1)

#### Inhaltsverzeichnis
* 01 - GitHub Account
* 02 - Git Client
* 03 - VirtualBox
* 04 - Vagrant
* 05 - Visual Studio Code
* 06 - Fazit
* 07 - Reflexion

01 - GitHub Account
======

Als erster Schritt muss ein GitHub-Account eingerichtet werden. Dieser dient uns später als "Cloud-Speicher" unserer Dokumentation und weiteren Dateien.

Folgende Arbeiten müssen gemacht werden:

### Account erstellen
***
1. Auf www.github.com ein Benutzerkonto erstellen (Angabe von Username, E-Mail und Passwort)
2. E-Mail zur Verifizierung des Kontos bestätigen und anschliessend auf GitHub anmelden


### Repository erstellen
***
1. Anmelden unter www.github.com 
2. Innerhalb der Willkommens-Seite auf <strong>Start a project</strong> klicken
3. Unter <strong>Repoository name</strong> einen Name definieren (z.B. M300)
4. Optional: kurze Beschreibung eingeben
5. . Radio-Button bei <strong>Public</strong> belassen
6. Haken bei <strong>Initialize this repository with a README</strong> setzen
7. Auf <strong>Crate repository</strong> klicken
   

### SSH-Key erstellen (lokal)
***
1.  XXX


### SSH-Key hinzufügen
***
1.  Anmelden unter www.github.com
2.  Auf Benutzerkonto klicken (oben rechts) und den Punkt <strong>Settings</strong> aufrufen
3.  Unter den Menübereichen auf der linken Seite zum Abschnitt <strong>SSH und GPG keys</strong> wechseln
4.  Auf <strong>New SSH key</strong> klicken
5.  Im Formular unter <strong>Title</strong> eine Bezeichnung vergeben (z.B. MB SSH-Key)
6.  Den zuvor kopierten Key mit <i>CTRL + V</i> einfügen und auf <strong>Add SSH key</strong> klicken
7.  Der Schlüssel (SSH-Key) sollte nun in der übergeordneten Liste auftauchen


02 Git Client
======

Damit die Arbeiten lokal auf dem eigenen PC erfolgen können, muss der sogenannte "Git Client" installiert werden. Dieser ermöglicht uns,
Cloud-Repositories zu klonen, zu pullen (herunteraden) oder ein lokales Repository zu pushen (hochladen).

Hierzu müssen folgende Schritte durchgeführt werden: 

### Client installieren
***
1. XXX


### Client konfigurieren
***
1. XXX


### Repository klonen
***
1. XXX

### Repository herunterladen (Pull)
***
1.  XXX


### Repository hochladen (Push)
***
1.  XXX


### Übersicht "How to Push"
***

```Shell 
git status  #Geänderte Datei(en) werden rot aufgelistet
git add -a  #Fügt alle Dateien zum "Upload" hinzu
git status  #(Optional) Der Status ist nun grün > Dateien sind Upload-bereit
git commit -m "Mein Kommentar" #Upload wird "commited" > Kommentar zu Dokumentationszwecken ist dafür notwendig
git status  #Dateien werden nun als "zum Pushen bereit" angezeigt
git push    #Upload bzw. Push wird durchgeführt
```



03 VirtualBox
======

04 Vagrant
======

05 Visual Studio Code
======

06 Fazit
======

07 Reflexion
======