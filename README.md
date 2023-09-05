# Esercizi - Risposta alle domande

1. Cos'è ReactJS?

React non è un 'framework'. Molti framework usano React, ma React non lo è.
I framework come ad esempio ReactNative, Next.js, Gatsby e Remix usano React per
creare interfacce utente, perché React è una libreria specializzata nella creazione di
queste interfacce. Proprio il suo essere "solo una libreria" ha portato allo sviluppo
di un vasto e rigoglioso ecosistema di librerie da usare insieme a React per costruire
applicazioni.

2. ReactJS è un framework, non una libreria. (=> falso)

3. Il file package.json contiene

- Molte informazioni utili, come ad esempio l'elenco di tutte le dipendenze richieste
dall'applicazione

4. create-react-app è l'unico modo possibile per creare un'applicazione React (=> falso)

5. Qual è il comando da lanciare nel terminale per creare una nuova create-react-app
con nome "test"?

- npx create-react-app test

6. Cos'è un componente Reeact?

- Un blocco di logica/contenuto riutilizzabile all'interno dell'applicazione

7. Un componente React può venire creato in tre modi: come funzione, classe o
interfaccia. (=> falso)

8. Qual è la differenza tra componenti creati come funzione e componenti creati
come classe?

- I componenti creati come funzione sono più semplici da scrivere, mentre i componenti
creati come classe necessitano in genere di un maggior numero di linee di codice.

9. Le props sono frammenti di informazione assegnati all'invocazione di un componente
React, utili al fine di rendere il componente dinamico e più riutilizzabile. (=> vero)

10. Le props possono essere passate solamente da un componente genitore ad un componente
figlio, non è possibile fare il contrario (=> vero)

11. Da dove possono venire recuperate le props all'interno di un componente React creato
come classe?

- Possono essere recuperate all'interno dell'oggetto 'this', dentro un sotto-oggetto
chiamato 'props'