# Instructions

This is a template that will help you to create **NodeJS** projects.

Ok, so now start an amazing projects!

## Commands

To install Dependencies:

```javascript
yarn
```

To Build `tsc` files (on `./dist` folder):

```javascript
yarn build
```

To run on dev enviroment:

```javascript
// Port 3333
yarn dev:server
```

## Visual Studio Code Settings

It's necessary install some plugins at your IDE to get the better of this template:

-   ESLint (dbaeumer.vscode-eslint)
-   Prettier Code Formatter (esbenp.prettier-vscode);

Type `Command + ,` and then add this configurations:

```javascript
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        },
        "editor.formatOnSave": true
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        },
        "editor.formatOnSave": true
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        },
        "editor.formatOnSave": true
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        },
        "editor.formatOnSave": true
    },
    "window.zoomLevel": 0,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
```
