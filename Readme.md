# Griglia Campo Minato

## Traccia

L'utente clicca su un bottone che genererà una griglia di gioco quadrata.
Ogni cella ha un numero progressivo, da 1 a 100.
Ci saranno quindi 10 caselle per ognuna delle 10 righe.
Quando l'utente clicca su ogni cella, la cella cliccata si colora di azzurro ed emetto un messaggio in console con il numero della cella cliccata.

---

## Bonus

Aggiungere una select accanto al bottone di generazione, che fornisca una scelta tra tre diversi livelli di difficoltà:

- con difficoltà 1 => 100 caselle, con un numero compreso tra 1 e 100, divise in 10 caselle per 10 righe;
- con difficoltà 2 => 81 caselle, con un numero compreso tra 1 e 81, divise in 9 caselle per 9 righe;
- con difficoltà 3 => 49 caselle, con un numero compreso tra 1 e 49, divise in 7 caselle per 7 righe;

---

## Steps

1. Prendiamo gli elementi dal DOM
2. Al click del bottone
   - Generiamo le celle nella griglia
   - Aggiungiamo un numero a ogni cella
     - Al click della cella
       - La cella si colora
       - Stampa in console il numero della cella
3. In base alla difficoltà
   - **SE** la difficoltà è hard crea un 7x7
   - **SE** la difficoltà è medium crea un 9x9
   - **SE** la difficoltà è easy crea un 10x10
