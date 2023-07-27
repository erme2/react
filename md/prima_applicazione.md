# Prima applicazione

(segue da [Installazione](./md/install.md))

Se guardiamo la cartella della applicazione appena creata dovremmo avere più o meno questa 
situazione

![default app dir](img/default_app.png)


## Main.tsx
Il file principale con il componente root é il file Main.js (o Main.tsx se stai usando 
Typescript) contenuto nella cartella `src`

```javascript
import React from 'react'
import ReactDOM from 'react-dom/client'
import App from './App.tsx'
import './index.css'

ReactDOM.createRoot(document.getElementById('root')!).render(
    <React.StrictMode>
        <App />
    </React.StrictMode>,
)
```
In questo caso il file main non fa altro che caricare il componente App.tsx.

## App.tsx
È il componente root della nostra applicazione. È un componente funzionale che ritorna
un elemento JSX. 

## Creiamo il nostro primo componente
Creiamo un nuovo file `Message.tsx` nella cartella `src` e scriviamo il seguente codice

```javascript