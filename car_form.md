<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Come fatto stamattina in classe potete fare un file di testo e scrivre la struttura li. 
-->

# Concessionario

## Scheda auto:

### __info principali__
* numero di serie | VARCHAR(17) - PRIMARY KEY - AUTO - UNIQUE - NOTNULL [WVW222AUZHP002856]
* serie limitata (n/100) | TINYINT [33]
* marca | VARCHAR(20) [MiniCooper]
* modello | VARCHAR [MINI_Paceman_Mini_Cooper_D_Paceman]
* tipologia | VARCHAR(30) [Station_Wagon]
* immatricolazione | DATE [2013_07_11]
* condizione | VARCHAR(20) [USATO]
* proprietari | TINYINT [2]
* distanza percorsa (km) | SMALLINT [87457]

### __prestazioni__
* alimentazione |
* cambio |
* rapporti |
* consumo urbano |
* consumo extraurbano |
* consumo misto |
* emissioni |
* velocità massima (km/h) |
* accelerazione (s) !
* peso minimo (kg) |
* peso massimo (kg) |

### __aspetto__
* lunghezza (mm) |
* larghezza (mm) |
* altezza (mm) |
* colore principale |
* colore secondario |
* porte |
* posti a sedere |
* interni |
* volume bagagliaio (l) |


### __ruote__
* pneumatici |
* materiale cerchioni |
* raggi |
* diametro cerchioni (mm) |

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




