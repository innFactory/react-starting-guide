# react-starting-guide
This is an instruction to react and related technics. Please go through it and prepare yourself for programming react! Have fun!

![header](header.png)

## Get Visual Studio Code
* [Download Visual Studio Code](https://code.visualstudio.com/download)


## NPM
* [What is npm?](https://docs.npmjs.com/getting-started/what-is-npm)
* [Install npm](https://docs.npmjs.com/getting-started/installing-node)

## React Basics
* [Video: What is React?](https://www.youtube.com/watch?v=JPT3bFIwJYA)
* [Tutorial: Intro To React](https://reactjs.org/tutorial/tutorial.html)
* [Video: State and Props](https://www.youtube.com/watch?v=qh3dYM6Keuw)
* [Another Starting Guide by Glitch](https://glitch.com/react-starter-kit)
* For more information and awesome repos:[awesome-react](https://github.com/enaqx/awesome-react)

### Inline Styles
We will use Inline Styles instead of putting the styles into separate CSS files (it's a very common practise in the react community). To see what inline styles are and how to use it visit the [repository of JSS](https://github.com/cssinjs/jss). There are some other libs like aphrodite which are providing also inline styles but JSS is our choice.

* Task: delete all css files in the tutorial above and use inline styles with JSS (You can defenitly play around, get familiar with styling and make it pretty)

## Redux
* [Video (watch from 0:00-1:30): Flux Architecture](https://www.youtube.com/watch?v=RbgU-zvbX1o)
* [Video: The theory behind redux](https://www.youtube.com/watch?v=D2MqT4OEgoE&index=2&list=PL55RiY5tL51rrC3sh8qLiYHqUV3twEYU_)

For later reading:</br>
* [Video: Async Actions and redux-thunk](https://www.youtube.com/watch?v=h892pHdLQtM&list=PL55RiY5tL51rrC3sh8qLiYHqUV3twEYU_&index=10)


## Typescript
* [What is Typescript?](https://medium.com/trisfera/the-basics-of-typescript-e46beeeffe1)
* [The benefits of TypeScript](https://medium.freecodecamp.org/when-should-i-use-typescript-311cb5fe801b)
* [The Typscript Book](https://basarat.gitbooks.io/typescript/content/docs/getting-started.html)

## Starting a project
Go to our template and follow the readme instruction:</br>
https://github.com/innFactory/create-react-app-material-typescript-redux


## Code Formatting with Visual Code
Download following extension: `vscode-tslint` (just search for tslint)
<br/>
Install tslint via npm:
```npm install -g tslint typescript```

Add following to your user settings in VSCode:
```
"editor.formatOnSave": true,
"tslint.enable": true,
"tslint.autoFixOnSave": true,
"typescript.updateImportsOnFileMove.enabled": "always",
"editor.codeActionsOnSave": {
        "source.organizeImports": true
},
"workbench.editor.showTabs": true,
"workbench.editor.enablePreview": false,
```

## Add code snippets for Visual Code
Add the the `typescriptreact.json` to your AppData folder e.g. `C:\Users\tonis\AppData\Roaming\Code\User\snippets` <br />
Use the snippet: Just type e.g. `reactcomponent` in a empty .tsx file for creating a new component.

## Cool Extensions for Visual Code
* Material Icon Theme by Philipp Kief `pkief.material-icon-theme`
* Auto Close Tag by Jun Han `formulahendry.auto-close-tag`
* Auto Rename Tag by Jun Han `formulahendry.auto-rename-tag`
* GitLens — Git supercharged by Eric Amodio `eamodio.gitlens`

