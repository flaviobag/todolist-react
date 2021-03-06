# Todolist usando REACT
## Continuação do projeto todolist mas agora usando o REACT 💻
https://github.com/flaviobag/todolist
<img align="right" alt="screenshot" src="https://user-images.githubusercontent.com/92397080/180434432-58b118a4-7822-440b-b1af-573855772c43.png" width="400px" />


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
## Descrição 📝
- Um aplicativo web para gerir suas coisas a fazer!
- Nele temos um cabeçalho com a data e hora atuais!
- Uma menssagem de acordo com a hora do dia e a quantidade de coisas a fazer!


## ✔️ Técnicas e tecnologias utilizadas

- ``JapaScript``
- ``HTML5``
- ``CSS/SASS``
- ``VS Code``

## Começando
 
Você irá precisar ter instalado o YARN ou NPM para usar essa aplicação ⬇️

Clone o projeto usando o git clone 
```
git clone https://github.com/flaviobag/todolist-react
```
Rode o comando para instalar as dependencias, pode ser o :
```
npm install
```
ou
```
yarn install
```
Para rodar o projeto :
```
npm start
```
ou 
```
yarn start
```

## Rodando o JSON server

Para ter a total funcionalidade do aplicativo, teremos que ter um servidor rodando em sua máquina, utilizaremos o json server.
Para começar instale o json server usando o comando
```
npm install -g json-server
```
Depois temos que criar um file chamado db.json com a seguinte estrutura 
```
{
  "notes": [
    {
      "value": "Tarefa 1",
      "id": 1
    },
    {
      "value": "Tarefa 2",
      "id": 2
    }
  ]
}
```
Em seguida temos que iniciar esse server local com o comando
```
json-server --watch db.json
```

## Melhorias previstas


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
