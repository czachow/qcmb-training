# Quantum Computing meets Business Training

## Einleitung

TODO

## Einrichtung

Das Tutorial kann sowohl über Google Colab genutzt werden, als auch über eine lokale Installation. Wir empfehlen die Nutzung von Google Colab für das Training, da die Schulung vollständig auf die Umgebung ausgelegt wurde.

### Google Colab

TODO

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
