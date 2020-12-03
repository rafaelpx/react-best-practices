# React Best Practices

$ npx create-react-app "APP_NAME"
$ yarn add eslint -D 
$ yarn run eslint --init

package.json, line 20, remove:

"eslintConfig": {
  "extends": [
    "react-app",
    "react-app/jest"
  ]
},

Successfully created .eslintrc.json file in root folder