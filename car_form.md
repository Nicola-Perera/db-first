<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Come fatto stamattina in classe potete fare un file di testo e scrivre la struttura li. 
-->

# Concessionario

## Scheda auto:

### __info principali__
* numero di serie | VARCHAR(17) - PRIMARY KEY - AUTO - UNIQUE - NOTNULL [WVW222AUZHP002856]
* serie limitata (n/100) | TINYINT - UNIQUE - NULL[33]
* marca | VARCHAR(20) - NOTNULL [MiniCooper]
* modello | VARCHAR(255) - NOTNULL [MINI_Paceman_Mini_Cooper_D_Paceman]
* tipologia | VARCHAR(30) - NULL [Station_Wagon]
* immatricolazione | DATE - NULL [2013_07_11]
* condizione | VARCHAR(20) - NULL [USATO]
* proprietari | TINYINT - NULL [2]
* distanza percorsa (km) | SMALLINT - NOTNULL [87457]

### __prestazioni__
* alimentazione | VARCHAR(20) - NOTNULL [Vapore]
* cambio | VARCHAR(20) - NOTNULL [Manuale]
* rapporti | TINYINT - NOTNULL [6]
* consumo urbano (l/100km) | FLOAT(3,1) - NULL [13,2]
* consumo extraurbano (l/100km) | FLOAT(3,1) - NULL [7,5]
* consumo misto (l/100km) | FLOAT(3,1) - NULL [9,6]
* emissioni | VARCHAR(10) - NOTNULL [Euro_5]
* velocità massima (km/h) | SMALLINT - NULL [250]
* accelerazione (s) | FLOAT(2,1) - NULL [6,1]
* peso minimo (kg) | SMALLINT - NULL [1.395]
* peso massimo (kg) | SMALLINT - NULL [1.925]

### __aspetto__
* lunghezza (mm) | SMALLINT - NULL [4.580]
* larghezza (mm) | SMALLINT - NULL [1.755]
* altezza (mm) | SMALLINT - NULL [1.470]
* colore principale | VARCHAR(20) -NULL [NERO]
* colore secondario | VARCHAR(20) - NULL [ORO]
* porte | TINYINT - NOTNULL [3]
* posti a sedere | TINYINT - NOTNULL [4]
* interni | VARCHAR(30) - NULL [Pelle]
* volume bagagliaio (l) | SMALLINT - NULL [430]


### __ruote__
* pneumatici | WARCHAR(255) - NULL [Michelin]
* materiale cerchioni | WARCHAR(255) - NULL [Ceri_in_lega]
* raggi | TINYINT - NULL [7]
* diametro cerchioni (inches) | TINYINT - NULL [18]

### __optional__
* volante in pelle | 
* controlli volante |
* vetri oscurati |
* vetri anti-proiettile |
* ABS |
* lanciarazzi anteriore |
* Cruise control |
* Servosterzo |
* climatizzatore |
* specchietti elettrici |




