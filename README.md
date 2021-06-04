# Quantum Computing meets Business Training

## Einleitung

TODO

## Einrichtung

Das Tutorial kann sowohl über Google Colab genutzt werden, als auch über eine lokale Installation. Wir empfehlen die Nutzung von Google Colab für das Training, da die Schulung vollständig auf die Umgebung ausgelegt wurde.

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
! git clone https://github.com/sva-qc-lab/qcmb-training.git
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

