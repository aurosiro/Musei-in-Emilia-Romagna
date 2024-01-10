**Musei in Emilia-Romagna**

In questo repository si trovano i file relativi al mio progetto per il quale ho analizzato i dati relativi ai visitatori annui dei musei dell’Emilia-Romagna. Ho ottenuto i dati tramite il database di Wikidata e li ho elaborati usando Excel. Avevo ottenuto 377 risultati, alcune di queste tuple non presentavano il numero dei visitatori annui, mentre altre avevano invece un numero di visitatori troppo basso perché potesse restituire dei risultati significativi per il progetto. Ho deciso di impiegare le tuple in cui il numero dei visitatori era superiore a 10000. Ho trasformato i dati in alcune tabelle e grafici pivot in modo da poter visualizzare l’evoluzione dei visitatori negli anni per museo e per città. Ho poi contato anche il numero dei musei a cui si riferivano questi dati.
_____________________________________________________________________________________________________________________________________________
**Svolgimento del progetto**

_Acquisizione_

Ho scritto una query per l’estrazione di un elenco dei musei situati in Emilia-Romagna contenente: il nome del museo, il luogo in cui si trova, le sue coordinate e i dati relativi ai visitatori annui insieme agli anni a cui si riferiscono.


_Elaborazione_	

Estraggo il risultato che mi è stato restituito da Wikidata in un file CSV, un formato tabellare adeguato a lavorare con dei fogli di calcolo e importo i dati in un nuovo foglio di lavoro Excel. 
Cancello le tuple che non sono utili per la mia ricerca e creo alcune tabelle e grafici pivot per visualizzare i dati.


_Condivisione_

Creo un repository su GitHub per condividere il progetto.
