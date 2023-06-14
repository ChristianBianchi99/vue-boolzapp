PROBLEMA : MILESTONE 1 : Replica della grafica e visualizzazione dinamica della lista contatti;

1 - START
2 - Realizzazione del markup statico;
3 - Costruzione della struttura di vue che andrà a contenere i dati dei contatti;
4 - Impostazione delle classi di stile che saranno gestite dalla parte di logica js;
5 - Implementazione di vue all'interno del Dom;
    5.1 - A questo punto verranno usati i dati all'interno di vue per creare dinamicamente la lista dei contatti;
6 - MILESTONE 1 FINISH

PROBLEMA : MILESTONE 2 : Visualizzazione dinamica dei messaggi e click sul contatto;

1 - START
2 - Creo la variante activeChat per poter poi stabilire quale chat visualizzare;
3 - Creo il ciclo for all'interno della sezione messages per poter visualizzare dinamicamente i messaggi della chat attiva in quel momento;
4 - Stabilisco le condizioni necessarie a visualizzare correttamente i messaggi della chat;
5 - Imposta il click sui contatti in modo da poter stabilire la chat attiva;
6 - FINISH

PROBLEMA : MILESTONE 3 : Aggiunta di un messaggio e risposta dall’interlocutore;

1 - START
2 - Creo la variante che andrà a contenere l'orario e la data odierna;
3 - Creo la funzione che al click dell'invio aggiunga il messaggio alla chat;
    3.1 - Prendo il contenuto dell'input della chat e alla pressione dell'invio ne faccio un oggetto che verrà pushato all'interno dell'array dei messaggi;
4 - Imposto la funzione che al click per l'invio di un messaggio attenda un secondo prima di inviare un messaggio di risposta preimpostato;
5 - FINISH

PROBLEMA : MILESTONE 4 : Ricerca utenti

1 - START
2 - Imposto una variabile che vada a contenere l'input per la ricerca dei contatti;
3 - Creo la funzione che andrà a ciclare i contatti e a verificare che i nomi presenti all'interno includano l'input dell'utente;
4 - ? SE uno dei nomi dei contatti ha delle corrispondenze con l'input;
    4.1 - La variabile visible rimarrà true;
5 - : ALTRIMENTI SE i nomi non avranno corrispondenze;
    5.1 - La variabile visible verrà impostata su false;
6 - Aggiungo infine la visualizzazione o meno dei contatti nel dom a seconda dello stato di visible;
7 - FINISH

PROBLEMA : MILESTONE 5 : Cancella messaggio e visualizzazione ora e ultimo messaggio inviato/ricevuto

1 - START
2 - Aggiunta nel markup di un dropdown sui messaggi con l'opzione per cancellarli;
3 - Creazione della funzione che recupererà l'indice del messaggio e lo andrà ad eliminare dall'array dei messaggi;
4 - Aggiunta della visualizzazione dell'ora e dell'ultimo messaggio inviato/ricevuto tra i dettagli dei contatti;
5 - FINISH
