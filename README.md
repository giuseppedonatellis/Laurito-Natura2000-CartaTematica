# Comune di Laurito – Carta dei siti Natura 2000

## Descrizione del progetto  
Questo progetto ha come obiettivo la realizzazione di una carta tematica dei siti della Rete Natura 2000 presenti nel territorio comunale di Laurito (SA). I dati sono stati ottenuti attraverso il servizio WMS del portale GN del Ministero dell’Ambiente, e rappresentano SIC, ZSC e ZPS ricadenti nel confine amministrativo comunale. La mappa è stata elaborata con QGIS e riporta la classificazione e distribuzione dei siti sul territorio.

## Obiettivo dell’esercitazione  
- Creare una carta dei siti Natura 2000 (SIC, ZSC, ZPS) tramite il servizio WMS ufficiale.  
- Riportare i siti individuati su una base georiferita locale.  
- Esportare una mappa in formato A4 (JPG, TIFF o PDF) completa di:  
  - Freccia del nord  
  - Barra di scala  
  - Legenda  
  - Coordinate  

## File principali  

### Layer vettoriali
- Poligoni_Rete-Natura-2000-Laurito.shp  
  → Poligoni dei siti Natura 2000 all'interno del territorio comunale, estratti o digitalizzati.

- Laurito.shp  
  → Confine amministrativo del Comune di Laurito (usato come base e per eventuali ritagli dei dati).

### Layer WMS  
- Servizio cartografico WMS:  
  https://gn.mase.gov.it/portale/servizio-di-consultazione-wms  
  → Utilizzato per visualizzare SIC, ZSC, ZPS nazionali.

### Progetto QGIS  
- Giuseppe Donatellis_step3.qgz  
  → Progetto completo con:
  - Layer dei siti Natura 2000.
  - Layer di base georiferito del Comune.
  - Composizione cartografica con elementi accessori (titolo, legenda, coordinate, ecc.).

### Output finale  
- Mappa A4 in formato .jpg, .tiff o .pdf con:  
  - Confine comunale  
  - Siti Natura 2000 colorati per categoria  
  - Freccia del nord, barra di scala, legenda, coordinate  
  - Scala adatta a visualizzare l’intera area comunale

## Coordinate di riferimento (CRS)  
- EPSG:32633 – WGS 84 / UTM zona 33N

## Software utilizzato  
- QGIS 3.30.x o superiore  
- Servizio WMS del portale GN  
- Plugin di composizione cartografica

## Flusso operativo  

1. Collegamento al WMS ufficiale per visualizzare i siti Natura 2000.  
2. Creazione del layer dei siti ricadenti nel Comune (clip o digitalizzazione).  
3. Simbologia dei poligoni secondo la tipologia (SIC, ZSC, ZPS, combinazioni).  
4. Composizione cartografica: inserimento legenda, freccia nord, barra di scala, coordinate.  
5. Esportazione della mappa in formato immagine A4 (JPG/TIFF/PDF).

## Risultati e applicazioni  
- Mappa tematica dei siti Natura 2000 utile per studi di conservazione, pianificazione e valutazione ambientale.  
- Supporto alla gestione del territorio e agli strumenti urbanistici locali.

## Autore  
Giuseppe Donatellis  
Corso GIS e Cartografia Geotematica – Università degli Studi di Napoli Federico II

## Suggerimenti per utilizzo futuro  
- Utilizzare la mappa per progetti ambientali, studi di incidenza o valutazioni VAS/VINCA.  
- Integrare con altri tematismi (uso del suolo, rete ecologica, habitat prioritari).

## Accesso ai dati
https://drive.google.com/drive/folders/1mpTT8YLGPuMddKwLqtt3NzeEdpJR6yyn?usp=drive_link
