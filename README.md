# Boardgame

Bnew Boardgame

# Version

```
node 18.17.0
npm 9.6.7
yarn 1.22.19
```

# Eslint

```
yarn create react-app [프로젝트명] - -template typescript
cd [프로젝트명]
yarn start
yarn add - -save react react-dom typescript
yarn add - -save-dev @types/react @types/react-dom @types/node
yarn create @eslint/config
```

```
How would you like to use ESLint?
- To check syntax, find problems, and enforce code style
What type of modules does your project use?
- JavaScript modules (import/export)
Which framework does your project use?
- React
Does your project use TypeScript?
- Yes
Where does your code run?
- Browser, Node 중복선택
How would you like to define a style for your project?
- Use a popular style guide
Which style guide do you want to follow?
- ????
How would you like to define a style for your project?
- prompt
What format do you want your config file to be in?
- JavaScript
What style of indentation do you use?
- tab
What quotes do you use for strings?
- double
What line endings do you use?
- windows
Do you require semicolons?
- Yes
```

# Eslint

```
yarn add -D prettier eslint-config-prettier
```

# vscode setting.json

```
{
  "code-runner.runInTerminal": true,
  "editor.codeActionsOnSave": { "source.fixAll.eslint": true },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.tabSize": 2,
  "prettier.endOfLine": "crlf"
}
```
