Assignment - frontend

Obiettivo: Creare un'applicazione web a pagina singola per gestire una lista di cose da fare (to-do list). L'applicazione dovrà consentire agli utenti di visualizzare, aggiungere, modificare ed eliminare le attività dalla lista utilizzando chiamate a una REST API.

Requisiti:

L'applicazione deve essere implementata utilizzando un framework front-end di tua scelta (ad esempio React, Angular o Vue.js).
La REST API per le operazioni CRUD è già fornita e documentata. Puoi utilizzare un'applicazione server fittizia (https://jsonplaceholder.typicode.com/):
GET /todos (e.g. https://jsonplaceholder.typicode.com/todos)
GET /todos/:todoid
POST /todos
PUT /todos/:todoid
PATCH /todos/:todoid
DELETE /todos/:todoid


L'applicazione deve mostrare un elenco delle attività presenti nella lista delle cose da fare.
Gli utenti devono essere in grado di aggiungere nuove attività alla lista utilizzando un modulo di inserimento.
Gli utenti devono essere in grado di modificare le attività esistenti nella lista utilizzando un'apposita funzione di modifica.
Gli utenti devono essere in grado di eliminare le attività dalla lista utilizzando un'apposita funzione di eliminazione.
L'applicazione deve effettuare le chiamate alle API utilizzando il metodo appropriato (GET, POST, PUT, DELETE) per ogni operazione CRUD.
L'applicazione deve gestire gli errori durante le chiamate alle API e fornire un feedback all'utente in caso di fallimento.
L'applicazione deve avere un design e un layout intuitivi e gradevoli.


Suggerimenti:

Puoi utilizzare librerie o strumenti come Axios o Fetch per effettuare le chiamate alle API REST.
Puoi utilizzare librerie o componenti UI predefiniti per la creazione dell'interfaccia utente, se preferisci.
Puoi organizzare il codice in componenti riutilizzabili per rendere l'applicazione più modulare.
Puoi utilizzare metodi di gestione dello stato come Redux o Context API per gestire i dati delle attività.
Presta attenzione alla gestione degli errori e alla validazione dei dati inseriti dagli utenti.
Assicurati di documentare le istruzioni di installazione e di eseguire l'applicazione nel tuo progetto.


BONUS: autenticazione

Scegliere un'API fittizia per l'autenticazione: Esistono diverse opzioni per utilizzare un'API fittizia per gestire l'autenticazione. Puoi considerare l'utilizzo di servizi come Firebase Authentication, JSON Web Token (JWT) o implementare un'API personalizzata con un database fittizio.

Definire le API per l'autenticazione: Crea le API necessarie per le operazioni di signup, signin e signout. Ad esempio, potresti avere le seguenti rotte:

POST /signup: Per registrare un nuovo utente.
POST /signin: Per autenticare un utente esistente.
POST /signout: Per disconnettere l'utente corrente.
