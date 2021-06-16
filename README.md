# Quantum Computing meets Business Training

Eine Schulungsserie der Meetup-Gruppe **[Quantum Computing meets Business - Rhineland](https://www.meetup.com/de-DE/Quantum-Computing-meets-Business-Rhineland/)**

## Einleitung

Basierend auf dem Material des IBM [Qiskit-Textbook](https://github.com/qiskit-community/qiskit-textbook) haben wir hier kostenfreies Schulungsmaterial für unsere Meetup Gruppe geschaffen. Das Schulungsmaterial ist in deutscher Sprache gehalten und nutzt das Qiskit Framework. Die Schulung gibt einen Einblick in die Funktionsweise von Quantencomputer und ihrer Programmierung. 

## Einrichtung

Das Tutorial kann sowohl über die IBM Quantum Experience, Google Colab, als auch über eine lokale Installation genutzt werden. Wir empfehlen die Nutzung der IBM Quantum Experience für das Training, da die Schulung vollständig auf die Umgebung ausgelegt wurde.

### IBM Quantum Experience

1. Öffnen Sie die IBM Quantum Experience unter https://quantum-computing.ibm.com/ und melden Sie sich an. Falls Sie noch keinen IBM Account besitzen, können Sie in diesem Schritt einen solchen erstellen.

2. Sobald Sie sich eingeloggt haben, wechseln Sie das Quantum Lab durch Drücken auf den Button in der linken Navigationsleiste: 

3. Erstellen Sie ein neues (leeres) Notebook durch Drücken auf den "New Notebook" Button.

3. Kopieren Sie die folgenden Instruktionen in das neue Notebook in eine leere Zelle.

```
!rm -rf qcmb-training && git clone https://github.com/czachow/qcmb-training.git
```

5. Führen Sie die Zelle durch Drücken der Kombination Shift+Enter aus. Nun werden die Instruktionen ausgeführt und nach einem Moment das Ergebnis dargestellt. Nach erfolgreicher Durchführung erscheint die Zeile Updating files: 100%, done.

6. Nachdem alle Instruktionen erfolgreich durchgeführt wurden, können Sie nun zurück zum Quantum Lab gehen. Dazu drücken Sie den Button Quantum Lab. 

7. In der Übersicht werden nun alle Notebooks des Workshops angezeigt:

8. Starten Sie das erste Notebook (./content/00-Inhalt_Tools.ipynb)[./content/00-Inhalt_Tools.ipynb]

### Google Colab

Google Colab wird innerhalb des Workshops dazu verwendet die Notebooks bereitzustellen und das Material zu nutzen. Um das Material dort abzuspeichern und damit zugänglich zu machen, verfährt man wie folgt.

1. Öffnen Sie ein neues leeres Notebook. 

2. Binden Sie ihr Google Drive in die aktuelle Instanz ein. 

```
from google.colab import drive
drive.mount("/content/gdrive")
```

3. Kopieren Sie das Material von der Github Website

```
! cd /content/gdrive/MyDrive/
! git clone https://github.com/czachow/qcmb-training.git
```

4. Öffnen Sie das erste Notebook im Ordner "qcmb-training/content/01-Uebersicht-Einfuehrung.ipynb"

### Lokale Installation

1. Für eine lokale Installation wird die Python Distribution Anaconda benötigt. Diese kann kostenlos unter folgender URL heruntergelanden werden [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual). Ihr liegt eine separate Installationsanleitung bei.
2. Das Material kann aus diesem Repository runtergeladen werden. Dazu bietet sich entweder die Software `git` an oder der Direktlink auf der Seite. Falls die Methode des Direktlinks verwendet wird muss das entsprechende ZIP-Archiv noch entpackt werden.
3. Nun öffnen Sie das Terminal bzw. die Kommandozeile und wechseln in den Ordner in welchem das Material abgelegt wurde.

```
cd "Your path here"/qcmb-training
```

4. Die Installation der Umgebung kann nun mittels des folgenden Befehls durchgeführt werden:

```
conda env create -f environment.yml 
```

5. Nach erfolgreicher Installation kann die Umgebung nun aktiviert werden:

```
conda activate qcmb-training
```

6. Starten Sie nun den Notebook Server, deiser leitet Sie automatisch in Ihren Browser weiter. Der Befehl lautet:

```
jupyter notebook 
```

