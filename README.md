Carosello Mono Array
===
Dato un array contenente una lista di cinque immagini, creare un carosello
## Svolgimento
1. Creo il markup statico in html e css
2. Tolgo il layout statico 
3. Inserisco le immagini da javascript e salvo le immagini in un array
4. Creo un ciclo dell'array con le immagini, in cui ad ogni ciclo aggiungo la classe 'hide'
5. Faccio crescere e decrescere il counter delle img al click del bottone up
6. Metto la classe 'hide' all'elemento che cresce o diminuisce, poi la tolgo dopo che è aumentato o diminuito
7. Rimuovo la classe hide al bottone down quando premo il bottone up e viceversa
8. Rimetto la classe hide al bottone down quando torno all'immagine iniziale
9. Rimuovo la classe hide al bottone up quando sono all'ultima immagine
10. Aggiungo la classe hide al bottone up quando arrivo all'ultima immagine