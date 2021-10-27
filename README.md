# Quantum Computing meets Business Training

Eine Schulungsserie der Meetup-Gruppe **[Quantum Computing meets Business - Rhineland](https://www.meetup.com/de-DE/Quantum-Computing-meets-Business-Rhineland/)**

## Einleitung

Basierend auf dem Material des IBM [Qiskit-Textbook](https://github.com/qiskit-community/qiskit-textbook) haben wir hier kostenfreies Schulungsmaterial für unsere Meetup Gruppe geschaffen. Das Schulungsmaterial ist in deutscher Sprache gehalten und nutzt das Qiskit Framework. Die Schulung gibt einen Einblick in die Funktionsweise von Quantencomputer und ihrer Programmierung. 

## Einrichtung

Das Tutorial kann sowohl über die IBM Quantum Experience und über eine lokale Installation genutzt werden. Wir empfehlen die Nutzung der IBM Quantum Experience für das Training, da die Schulung vollständig auf die Umgebung ausgelegt wurde.

### IBM Quantum Experience

1. Öffnen Sie die IBM Quantum Experience unter [https://quantum-computing.ibm.com/](https://quantum-computing.ibm.com/) und melden Sie sich an. Falls Sie noch keinen IBM Account besitzen, können Sie in diesem Schritt einen solchen erstellen.

2. Sobald Sie sich eingeloggt haben, wechseln Sie in den Bereich **Quantum Lab** durch Drücken auf den entsprechenden Button.

3. Starten Sie den Jupyter Server durch Drücken auf den Button "Lauch Server".

4. Erstellen Sie ein neues (leeres) Notebook durch Drücken auf den Button "New".

5. Wählen Sie anschließend im zentralen Feld in der Kategorie "Notebook" die Version "Qiskit 0.xx.xx (ipykernel)".

6. Kopieren Sie die folgenden Instruktionen in das neue Notebook in eine leere Zelle.

```
!rm -rf qcmb-training && git clone https://github.com/czachow/qcmb-training.git
```

7. Führen Sie die Zelle durch Drücken der Kombination Shift+Enter aus. Nun werden die Instruktionen ausgeführt und nach einem Moment das Ergebnis dargestellt. Nach erfolgreicher Durchführung erscheint die Zeile Updating files: 100%, done.

8. Nachdem alle Instruktionen erfolgreich durchgeführt wurden, können Sie nun zurück zum Quantum Lab gehen. Dazu drücken Sie den Button Quantum Lab. 

9. In der Übersicht werden nun alle Notebooks des Workshops angezeigt:

10. Starten Sie das erste Notebook [./content/00-Inhalt_Tools.ipynb](./content/00-Inhalt_Tools.ipynb)

### Lokale Installation

1. Für eine lokale Installation wird eine Python Distribution benötigt. Wir empfehlen die Benutzung des kostenlosen Anaconda-Nachbaus namens conda-forge. Diese kann kostenlos unter folgender URL heruntergelanden werden [https://github.com/conda-forge/miniforge](https://github.com/conda-forge/miniforge). Dort finden Sie auch eine separate Installationsanleitung.
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

