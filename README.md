# Appunti ReactJS

React é una libreria JS per costruire UIs (User Interface). Il cuore di ReactJS sono i componenti.

## I components
I components sono parti di UI ed hanno queste specifiche caratteristiche:

- Indipendenti
- Isolati
- Riutilizzabili

Questi components sono come i mattoncini dei lego e li utilizzeremo per costruire le interfacce 
utente come utilizziamo i mattoncini dei lego per costruire i nostri capolavori!

Ogni applicazione React ha almeno un component cui faremo riferimento come al `root` component e 
rappresenta l'applicazione principale. Il root component funziona anche come contenitore per 
tutti i `child` components. L'app React é come un albero, con il tronco (radice) -> `root` 
component e tanti rami e foglie -> `child` components.

### Implementazione
Ogni component viene implementato come una classe JS che deve sempre avere una proprietà status
e una funzione render.

```javascript
class Tweet {
    state = {};
    render () {
        
    }
}
```
La proprietà `state` contiene i dati, o il codice html che vogliamo venga rappresentato quando 
verrà chiamata la funzione `render`.
L'output della funzione `render` é il componente react. Il componente react é un semplice 
oggetto JS che rappresenta uno specifico elemento all'interno del DOM (Document Object Model).
React crea una copia semplificata del DOM chiamato React DOM, e tiene continuamente questi 
due oggetti collegati e aggiornati tra loro. 
Ogni cambiamento dell'uno si riflette automaticamente sull'altro. Questo significa the aggiornando
una proprietà dell'elemento react comporterà un immediato ed automatico aggironament dell'elemento 
html all'interno del DOM.

## [Installazione](./md/install.md)
## [Prima applicazione](./md/prima_applicazione.md)






