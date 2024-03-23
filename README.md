# Database di Viaggi
Questo repository contiene un database di viaggi creato utilizzando SQL tramite Beekeeper Studio.
Il database include informazioni dettagliate sulle città, compresi i costi dei trasporti per raggiungerle da Torino, consigli sulle visite e altro ancora.

![Screenshot 2024-03-23 012651](https://github.com/DavideGenovese/Database-SQL_Viaggi/assets/157692968/c47308de-f7d6-4a9c-8e8b-cedb3071e4a5)

## Struttura del Database
Il database è composto principalmente da una tabella che elenca diverse città e le relative informazioni sui trasporti e i consigli di viaggio.
La tabella principale include campi come:
* Città: Il nome della città.
* Giorni: Il giorni consigliati per godere a pieno della città.
* Pass: I pass per musei e/o trasporti
* Trasporti: I mezzi di trasporto disponibili nella città
* Costo Aereo: Il costo per raggiungere la città in aereo da Torino.
* Tempo Aereo: Il tempo necessario per raggiungere la città in aereo da Torino.
* Costo Treno: Il costo per raggiungere la città in treno da Torino.
* Tempo Treno: Il tempo necessario per raggiungere la città in treno da Torino.
* Costo auto: Il costo per raggiungere la città in auto da Torino.
* Ore in auto: Il tempo necessario per raggiungere la città in auto da Torino.
* Voto Città: Il mio consiglio sulla città.
## Utilizzo
Puoi utilizzare questo database per pianificare i tuoi viaggi da Torino verso diverse destinazioni. Ecco come puoi accedere e interrogare il database:

#### 1: _Apri Beekeeper Studio_
#### 2: _Aprire Xampp e abilitare Apache e MySQL_
#### 3: _Connetti il tuo database SQL che contiene le tabelle dei viaggi._
#### 4: _Esegui le query SQL per ottenere informazioni specifiche sulle città, i costi dei trasporti e i consigli generali sulle città._
## Esempio di query
Ecco un esempio di query SQL per ottenere le informazioni su una città specifica:
```sql
select *
from informazioni_viaggi
where Città="Roma"
```
Questo restituirà tutte le informazioni disponibili su Roma.
## Autore
Davide Genovese
