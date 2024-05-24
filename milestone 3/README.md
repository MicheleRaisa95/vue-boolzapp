Milestone 1
Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto

1. uso array fornito per recuperare i dati necessari
2. uso v-for per viusalizzare nomi e immagini dei contatti contenuti nell array
3. nell html uso v-bind per collegare l'attributo
4. uso un methods per la gestione dei click dei contatti che mi consente di vedere la chat corrispondente

Milestone 2
Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
Click sul contatto mostra la conversazione del contatto cliccato

1. nella sidebar aggiungo un gestore di click su ogni contatto

2. nel pannello della conversazione devo:
- mostrare l'avatar del contatto selezionato
- usare v-for per iterare sui messaggi e mostrarli
- aggiungere un controllo per quando nessun contato viene selezionato?

Milestone 3
Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde
Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.


1. Gestione invio dei messaggi:

- aggiungo un metodo per gestire l'invio del messaggio 
- recupero il testo dal campo di imput
- creo un nuovo messaggio con la data corrente e che risulti inviato
-aggiungo il messasggio all'array messages del contatto selezionato
-pulisco il campo di input

2. Risposta automatica:

- Dopo ivio mesaggio uso un timeout per simulare una risposta 
- creo un nuovo messaggio con il testo ok
- aggiungo il messaggio all'array del contatto 



