# SCSS Sandbox
SCSS / SASS Sandbox with main usage examples for personal practice

How to use:

Initialize and create the package.json
`npm init -y`

Inside package.json, make sure to add "sass" inside "scripts":
```
"scripts": {
    "sass": "node-sass -w scss/ -o dist/css --recursive"
  },
  ```

Install SCSS/SASS compiler "node-sass":
`npm install node-sass`

Run "node-sass" and it will compile the .scss into .css on save:
`npm run sass`