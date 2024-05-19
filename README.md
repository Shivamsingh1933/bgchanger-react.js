# React + Vite
<br>
#COMMANDS
<br>
1). "npm create vite@latest"
<br>
<br>
2). "npm install (for installing the node _modules)"
<br>
<br>
3). "npm install -D tailwindcss postcss autoprefixer
    <br>
    npx tailwindcss init -p( for installing the tailwind css)"
    <br>
    <br>
4). In tailwind.config.css modify the content section by this 
"content: [
    "./index.html",
    <br>
    "./src/**/*.{js,ts,jsx,tsx}",
  ],"
  
  <br>
  <br>

5). add these library of tailwind in index.css in the src folder for using tailwind in better way 
"@tailwind base;
<br>
@tailwind components;
<br>
@tailwind utilities;</h2>"
<br>
<br>

6). finally the command for running the project is "npm run dev"
    

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

<h2>THE MAIN FOCUS IN THIS PROJECT WAS TO UNDERSTAND ABOUT THE OnClick FUNCTION THAT HOW IT'S A FUNCTION AND PARAMETERS ARE PASSED FOR THE COLORS AND BACKGROUND GETS CHANGED. </h2>

<H2> In app.jsx firstly function app() is created then a const array is there where we will pass 2 paramets of color and SetColor then useState that is used for initially tell what the color will be when we refresh the webpage and finally the div tag and button is used to tell how background color will be changing by using OnClick function</H2>
