# MARVEL APP :atom_symbol:
This project has like purpose to consume [API da MARVEL](https://developer.marvel.com/) display for the user a project with [React](https://pt-br.reactjs.org/). To request the datas was used in this project the package ```axios```.

## Visit the website :link:

This web app can visited by the link: [https://yapily-marvel-test.vercel.app/](https://marvel-app.vercel.app/)

Published by [Vercel](https://vercel.com/).

## About the project 

The homepage lists the characters, it is possible to navigate between the paginations.

Clicking on a character's card will redirect you to the page that details the respective character. There it will be possible to view more information, below there is a list of comics in which the character had his participation.

### Technologies used
- [React](https://pt-br.reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Styled Components](https://styled-components.com/)
- [TypeScript](https://www.typescriptlang.org/)


## Vamos começar? :smiley:
### How to install the project

After clone repository [repository Github](https://github.com/rsperlongo/yapily-marvel-test), navitage to root of the project, open up the terminal and execute this command

This command will install all required dependencies to execute the project.
```BASH
npm install 
```

After install dependencies, after install dependencies we can also use some more commands.

### :construction: Development enviromment 
Execute project in a local development enviroment.
```BASH
npm run dev
```

### :wrench: Project Build
Run project build.
```BASH
npm run build
```

## Project directories structures

### src
This directory is where has all code developed, in another words, lógic application, components, pages, routes, services and so on.

### components/elements
Has only static elements, should be used in ```components/modules``` or even in ```/pages```.

### components/modules
Has more deep logics, aqueles que podem conter lógica e/ou receber ```props```.

### pages
Has the view pages.

### services
Where has the application logic connection, for example [API da MARVEL](https://developer.marvel.com/). 

### styles
Pages stylesheet and globals stylesheet.