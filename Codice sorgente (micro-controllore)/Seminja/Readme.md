SEMINJA

Il progetto è stato sviluppato su ambiente di sviluppo Eclipse.
Utilizzando le librerie standard dell'esp32 si sono aggiunte le librerie:

-sensor per comunicare con il sensore di temperatura e umidità
-fetch per efettuare le chiamate alle api di tim

Si sfruttano i due core dell'esp32, il primo core si dedica alla connettività mentre il secondo core si dedica ai sensori

La scheda genera un wifi per comunicare con l'utente, se nessuno è collegato ogni 10 secondi si collega ad una rete wifi domestica
per efettuare le chiamate alle API.