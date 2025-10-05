# Progetto EICA: Gestione File DICOM

**Descrizione**  
Progetto universitario EICA per la gestione di file DICOM: permette di selezionare manualmente una ROI (area di interesse), salvare le immagini crop con testo informativo sovrapposto e generare un video MP4 dai frame selezionati.

**Funzionalità principali**
- Inserimento interattivo delle informazioni del paziente.
- Selezione manuale della ROI sul primo frame.
- Crop di tutti i frame del DICOM e salvataggio come immagini JPEG.
- Sovrapposizione automatica del testo informativo (paziente, esame, reparto, data).
- Creazione automatica di un video MP4 con tutte le immagini crop.
- Salvataggio del file DICOM aggiornato con le informazioni inserite.

**Requisiti**
- Python 3.11+
- Librerie Python:
  - `pydicom`
  - `numpy`
  - `opencv-python`
  - `Pillow`
  - `matplotlib`

**Uso**
1. Apri il progetto in Visual Studio Code.
2. Attiva un ambiente virtuale (consigliato).
3. Installa le librerie richieste:
   ```bash
   pip install pydicom numpy opencv-python Pillow matplotlib
I file DICOM reali, immagini e video generati non sono inclusi nel repository per motivi di privacy e dimensione.
