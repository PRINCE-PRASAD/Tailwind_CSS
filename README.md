## To set up Tailwind CSS run this commands.
1. npm init can be used to set up a new or existing npm package. 
```
npm init -y
```
2. Installing Tailwind CSS as a PostCSS plugin
```
npm install -D tailwindcss postcss autoprefixer
```
3. Generate a Tailwind config file and postcss.config.js for your project using the Tailwind CLI utility included
```
npx tailwindcss init -p
```
4. Vite. js allows developers to set up a development environment for frameworks like Vue, TezJS and React and even for Vanilla JavaScript app with a dev server.
```
npm i vite
```
5. Create a css file "input.css" and index.html and add css(link) to your html file.

6. Add this line of code to input.css.
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
7. Replace content: [ ] with content: ["*"] in the tailwind.config.js

8. Add the following Script in package.json
```
    "scripts": {
    "start": "vite"
    },
```
9. Run this command to start a dev server.
```
npm run start
```
