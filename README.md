esercizio di oggi(12/07/24): *Social Posts*
*nome repo:* js-social-posts

*Descrizione*
Ricreiamo un feed social aggiungendo al layout di base fornito, il nostro script JS in cui:

*Milestone 1* - Prendendo come riferimento il layout di esempio presente nell'html, stampiamo i post del nostro feed attraverso javascript.

*Milestone 2* - Se clicchiamo sul tasto "Mi Piace" cambiamo il colore al testo del bottone e incrementiamo il counter dei likes relativo.
Salviamo in un secondo array gli id dei post ai quali abbiamo messo il like.

*Numero push minimo: 10/12*
P.S. Occhio al nome della repo! Ricordatevi che deve essere js-social-posts!

*BONUS*
1. Formattare le date in formato italiano (gg/mm/aaaa)
2. Gestire l'assenza dell'immagine profilo con un elemento di fallback che contiene le iniziali dell'utente (es. Luca Formicola > LF).
3. Al click su un pulsante "Mi Piace" di un post, se abbiamo già cliccato dobbiamo decrementare il contatore e cambiare il colore del bottone.

*Consigli del giorno:*
Ragioniamo come sempre a step.
Prima scriviamo nei commenti la logica in italiano e poi traduciamo in codice.
console.log() è nostro amico.
Quando un pezzo di codice funziona, chiediamoci se possiamo scomporlo in funzioni più piccole.


*|SOLUZIONE|*

MILESTONE 1
1.-Recupero il contenitore dal DOM

2.-Effettuo un CICLE FOREACH dove ciclo tutti gli oggetti presenti nell'ARRAY
2.1.-Inserisco nel container recuperato tutti gli elementi dell'HTML

MILESTONE 2
3.-Recupero il bottone per il like

4.-Creiamo un secondo array dove verranno inseriti gli ID dei post al quale abbiamo messo like

5.-Creo un evento click 
5.1.-Il colore del bottone deve cambiare e diventare verde
5.2.-Il counter dei like deve aumentare di 1

