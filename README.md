# Tutoriel : intro à React

Nous allons construire un petit jeu pendant ce tutoriel. Vous pourriez être tenté·e de l’ignorer sous prétexte que vous ne construisez pas de jeux—mais donnez-lui sa chance. Les techniques que vous apprendrez dans ce tutoriel sont fondamentales pour la construction de n’importe quel type d’appli React, et les maîtriser vous apportera une compréhension profonde de React.

## Astuce

Ce tutoriel est conçu pour les personnes qui préfèrent apprendre en faisant. Si vous préférez apprendre les concepts à partir de la base, jetez un œil à notre guide pas à pas. Vous constaterez peut-être que le guide et ce tutoriel sont complémentaires l’un à l’autre.'

### Le tutoriel est découpé en plusieurs sections :

Mise en place du tutoriel vous donnera un point de départ pour suivre le tutoriel.
Aperçu vous apprendra les fondamentaux de React : composants, props et état local.
Finaliser le jeu vous apprendra les techniques les plus courantes de développement React.
Ajouter du voyage dans le temps vous donnera une perception plus approfondie des forces particulières de React.
Il n’est pas nécessaire de compléter toutes les sections d’un coup pour tirer le meilleur parti de ce tutoriel. Essayez d’aller aussi loin que vous le pouvez—même si ce n’est qu’une ou deux sections.

### Que construisons-nous ?
Dans ce tutoriel, nous allons voir comment construire un jeu de morpion interactif avec React.

Vous pouvez voir ce que ça va donner ici : résultat final. Si le code vous semble obscur, ou si vous n’êtes pas à l’aise avec la syntaxe du code, ne vous inquiétez pas ! C’est justement l’objectif de ce tutoriel de vous aider à comprendre React et sa syntaxe.

Nous vous conseillons de jeter un coup d’œil à ce jeu de morpion avant de continuer ce tutoriel. Une des fonctionnalités que vous remarquerez, c’est qu’il affiche une liste numérotée sur la droite du plateau de jeu. Cette liste vous fournit un historique des tours de jeu, et elle est mise à jour au fil de l’eau.

Vous pouvez refermer le jeu de morpion une fois que vous en avez bien fait le tour. Nous commencerons par un gabarit plus simple pour ce tutoriel. Notre prochaine étape consiste à mettre le nécessaire en place, sur votre machine, pour que vous puissiez commencer à construire le jeu.

### Prérequis
Nous supposerons que vous êtes un minimum à l’aise avec HTML et JavaScript, mais même si vous venez d’un autre langage de programmation vous devriez être capable de suivre le déroulé. Nous supposerons aussi que vous connaissez déjà les notions de programmation telles que les fonctions, objets, tableaux, et dans une moindre mesure, les classes.

Si vous avez besoin de réviser votre JavaScript, nous vous conseillons la lecture de ce guide. Remarquez que nous utilisons aussi certains aspects d’ES6—une version récente de JavaScript. Dans ce tutoriel, on utilise les fonctions fléchées, les classes, et les instructions let, et const. Vous pouvez utiliser la REPL Babel pour examiner le résultat de la compilation de code ES6.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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
