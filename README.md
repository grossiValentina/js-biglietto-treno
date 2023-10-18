####ESERCIZIO: calcolo del prezzo del biglietto del treno
_Il programma dovrà chiedere all'utente il numero di chilometri che vuole percorrere e l'età del passeggero.
Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
il prezzo del biglietto è definito in base ai km (0.21 € al km)
:bambino:  va applicato uno sconto del 20% per i minorenni
:donna_anziana:  va applicato uno sconto del 40% per gli over 65.
L'output del prezzo finale va messo fuori in forma umana (con massimo due decimali, per indicare centesimi sul prezzo)._

####Soluzione:

#####Dati:
1. Chiedere all'utente quanti chilometri vuole percorrere
2. Chiedere all'utente l'età

#####Logica:
1. Calcolo il prezzo del biglietto moltiplicando il numero di chilometri da percorrere per 0.21

2.
IF l'età dell'utente è <= 65 anni
      elaboro messaggio "E' stato applicato il 40% di sconto" 

ELSE IF l'età dell'utente è <= 18 anni e >=64 anni
       elaboro messaggio "Nessuno sconto applicato"

ELSE l'età dell'utente è >= 17 anni
      elaboro messaggio "E' stato applicato il 20% di sconto"
     

#####Ouput:
Stampo il messaggio in pagina con il prezzo finale del biglietto 
