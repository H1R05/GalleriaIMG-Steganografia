# Galleria Immagini con Steganografia - Project Work DevOps 2025

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange) ![Pillow](https://img.shields.io/badge/Pillow-Image_Processing-lightgrey) ![Stegano](https://img.shields.io/badge/Stegano-Steganografia-green) ![Licenza MIT](https://img.shields.io/badge/license-MIT-green)

Benvenuto nel mio progetto GitHub! 🎉 Sono Samuele, uno studente DevOps appassionato di tecnologia e del mondo informatico.Questo progetto sfrutta la potenza dell’informatica per esplorare la steganografia digitale, una tecnica che permette di nascondere informazioni all’interno di immagini senza modificarne l’aspetto visibile.

Storicamente utilizzata per comunicazioni segrete, la steganografia ha attraversato i secoli, dai messaggi celati dagli antichi Greci alle strategie crittografiche moderne.Tecnicamente, il progetto implementa la modifica dei bit meno significativi (LSB - Least Significant Bit), una tecnica avanzata che altera i singoli pixel dell’immagine per incorporare dati nascosti.
In pratica, una piccola variazione nel valore di un pixel, impercettibile all’occhio umano, consente di codificare informazioni senza compromettere la qualità visiva dell’immagine.

✨ Funzionalità Principali
🔹 Esplora le immagini in modalità griglia o presentazione 
🔹 Ricerca dinamica per trovare rapidamente i file 
🔹 Filtri avanzati per selezionare formato e caratteristiche 
🔹 Steganografia interattiva:

✨ Nascondi un messaggio in un'immagine (solo PNG)

🔎 Estrai un messaggio segreto da un'immagine

🔹 Interfaccia elegante con ttkbootstrap e supporto modalità scura 
🔹 Navigazione intuitiva con scorciatoie da tastiera (← e →)

🎨 Anteprima dell'Interfaccia
![Anteprima GUI](./screenshots/ScreenshotGUI2025.png)
> Un'interfaccia pulita e intuitiva basata su Tkinter + ttkbootstrap, perfetta per esplorare il mondo nascosto della steganografia.

🛠️ Tecnologie Utilizzate
🔹 Python 3.x 
🔹 Tkinter + ttkbootstrap (GUI moderna e responsiva) 
🔹 Pillow (gestione immagini) 
🔹 stegano (steganografia LSB)

🚀 Avvia il Progetto e Diventa un Maestro della Steganografia
## 🔧 Requisiti
Assicurati di avere Python 3 installato. Ti consiglio di creare un ambiente virtuale per evitare conflitti tra pacchetti:
```bash
# Creazione di un ambiente virtuale
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows

# Ora installa le dipendenze necessarie:
pip install -r requirements.txt
```
```bash
# Avvio dell'applicazione
python main.py
```
🕵️ Come Funziona la Steganografia?
Nel mondo digitale, nascondere un segreto è più semplice di quanto sembri. La steganografia non modifica visibilmente un’immagine, ma inserisce informazioni nei pixel usando tecniche avanzate.

💡 Esempio pratico in Python:
```python
from stegano import lsb

# Nascondere un messaggio segreto
lsb.hide("input.png", "Messaggio segreto").save("output.png")

# Estrarre il messaggio nascosto
hidden_message = lsb.reveal("output.png")
print("Messaggio estratto:", hidden_message)
```

👨‍💻 **Creato da:** [Samuele](https://github.com/H1R05)  
