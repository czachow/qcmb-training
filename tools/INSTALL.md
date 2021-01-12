## Hilfe Datei für die Installation

* Installation *

- Während des Workshops empfehlen wir die Benutzung von Google Colab. Hier lassen sich alle Abhängigkeiten einfach installieren und die Schulung ist vollständig auf diese Umgebung ausgelegt. Während des Workshops können wir weitere Zugriffsmodelle nicht unterstützen. 
- Eine Einrichtung einer ähnlichen Umgebung ist mithilfe untenstehender Anleitung möglich. 

* Cloud Installation * 
TODO: Zugriff auf die Ordner im Github


* Private Installation *

    1. Laden Sie die Ananconda Python Distribution von www.anaconda.com herunter. 
    2. Installieren Sie die Distribution in den gewünschten Pfad.
    3. Starten Sie Ihre präferierte Konsole im Home-Ordner von qcmb-training und überprüfen Sie die erfolgreiche Installation. 
        'conda list'
    4. Erstellen Sie eine virtuelle Umgebung
        ' conda create --name qcmb-training python=3.7 '
    5. Aktivieren Sie die Umgebung
        ' conda activate qcmb-training '
    6. Installieren Sie die benötigten Pakete
        ' pip install -r tools/requirements.txt
    7. Starten Sie den Jupyter Notebook Server
        ' jupyter notebook & ' 
