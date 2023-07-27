# Install

// todo [DA AGGIORNARE](https://create-react-app.dev/docs/getting-started/)

Per creare un progetto ReactJS avremo bisogno di installare NodeJS e NPM, se avete un mac e
`brew` installato basterà
```shell
brew install node
```
In caso contrario potete far riferimento al sito ufficiale [NodeJS](https://nodejs.org/en)
nella sezione [download](https://nodejs.org/en/download)


Si possono usare due metodi per creare un progetto ReactJS:
- cra -> create-react-app
- vitejs

## Create React App
Dobbiamo installare questo primo pacchetto a livello globale
```shell
// su macos potresti aver bisogno di 
```s
npm i -g create-react-app
create-react-app my-app
```
## ViteJS
```shell

npm create vite@4.1.0 // for a specific version
npm create vite@latest // for the latest version
npm init vite@latest  // for the latest version

// example
$ npm init vite@latest
Need to install the following packages:
  create-vite@4.4.1
Ok to proceed? (y)      y
✔ Project name: … react-app
✔ Select a framework: › React
✔ Select a variant: › TypeScript

Scaffolding project in /Volumes/code/learn/react/react-app...

Done. Now run:

  cd react-app
  npm install
  npm run dev




npm init vite@latest my-react-app --template react // all in one command

```
Continua qui -> [Prima applicazione](./md/prima_applicazione.md)

[index](../README.md)