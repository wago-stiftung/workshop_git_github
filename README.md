# Workshop: Git/Github with Github Desktop

## Intro

### 1. Git
Egal ob Quellcode, Grafikdatei oder Dokumentation – Arbeitsfortschritte sollte man versionieren, um
später auf ältere Versionsstände zurückgreifen zu können. Git ist ein frei verfügbares dezentrales Versionskontrollsystem. 
Es ermöglicht 
- Versionierung
- Dokumentation/Protokollierung
- Kollaboration
Die Daten werden dabei in sogenannten Repositories gespichert. Jeder Entwickler hat eine vollständige Arbeitskopie des jeweiligen Repositorys auf seinem Rechner. Auf Linuxsystemen ist es in der Regel standardmäßig als Konsolenanwendung verfügbar (2005 von Linux Torvalds entwickelt). Zudem gibt es für alle Systeme (Mac/Windows) grafische Oberflächen.

#### Workflow
Abbildung hier einsetzen

### 2. Github
Github ist eine Plattform zur Verwaltung von Git-Repositories. Repositories bis 500 MB sind kostenfrei und können öffentlich oder privat sein.

### 3. Github Desktop
Grafische Oberfläche für Git, welche für die Nutzung mit Github optimiert ist.


## Hands-on
Es wird eine Python-Bibliothek implementiert, welche die mathematischen Funktionen 
- Addieren -> add(zahl1, zahl2),
- Subtrahieren -> sub(zahl1, zahl2),
- Multiplizieren -> mul(zahl1, zahl2) und
- Dividieren -> div(zahl1, zahl2) 
zur Verfügung stellt.  

### Vorbereitung auf Github
1. (kostenlosen Account anlegen)
2. neues Repository (pythonmath) erstellen --> Readme.md
3. README.md online bearbeiten
4. Issues erstellen


### Clonen mit Github Desktop
1. Repository clonen (from url)
2. Repository in VS Code öffnen
3. Leere Datei python_math.py hinzufügen
4. Funktion zum Addieren und Subtrahieren lokal implementieren

    ``` python
     def Add(zahl1, zahl2):
        return zahl1 + zahl2
    ```
5. commit
6. push
7. Issues schließen
8. Funktion zum Subtrahieren auf Github implementieren

    ``` python
     def Sub(zahl1, zahl2):
        return zahl1 - zahl2
    ```
9. commit (Github)
10. Lokal pull
11. Funktion zum Dividieren auf Github implementieren

    ``` python
     def Div(zahl1, zahl2):
        return zahl1 / zahl2
    ```
12. commit (Github)
13. Funktion zum Multiplizieren lokal implementieren

    ``` python
     def Mul(zahl1, zahl2):
        return zahl1 * zahl2
    ```
14. commit
15. push
16. conflict -> merge

    

### ggfs. arbeiten auf der Linux-Konsole (z.B. Raspi)
