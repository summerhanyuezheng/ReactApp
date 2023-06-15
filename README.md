# ReactApp
# Project Description
# VScode setup:
### Json file configure: 
`"files.associations": {
        "*.js":"javascriptreact"
    }` : added this configuration in vscode so the files are kept under Javascript JSX environment without switching
### Extension "Prettier" configure for VScode:
  - `"editor.defaultFormatter": "esbenp.prettier-vscode",`
  - `"editor.formatOnSave": true,`
  - `"prettier.semi":false,`
  - `"prettier.printWidth": 9999,`
  - `"editor.tabSize":2`
  - `"prettier.arrowParens": "avoid",` : allow you to write an arrow function and if you have exactly one parameter you can skip the parentheses without Prettier adding them in for you
  - `"prettier.trailingComma": "none"`
# Project Workflow Setup:
  - `npm init -y`: initialize package.json file (terminal)
  - `npm install react react-dom`: using npm to install react and react-dom(for web applications)(terminal)
  - `npm install webpack webpack-cli webpack-dev-server`, (this bundle help website knowing that it's JSX code and makes sure everything works on the clients' side)  (terminal)
  - created file `webpack.config.js` and its configuration code
  - `npm install @babel/core @babel/preset-env @babel/preset-react babel-loader` (terminal)
  - in package.json, added my own script for running webpack: ` "dev": "webpack serve" `
  - `npm run dev`: using the script just created to run webpack (terminal)
  - added Hot Module Replacement(HMR) in main.js, it allows updates without reloads. `if (module.hot){
  module.hot.accept()}`
    
# Technology used
  - React(JSX)
  - Node.js
  - Webpack
