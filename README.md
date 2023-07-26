# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Se utiliza la Desestructuración
debemos comprender que useState regresa un arreglo donde:

•	La posición cero es el state

•	Y la segunda posición es una función que nos permite modificar el valor del state.

#Crear un nuevo proyecto
 
Con NPM:
$ npm create vite@latest
Con Yarn: 
$ yarn create vite

Puede especificar directamente el nombre del proyecto y la plantilla que desea usar a través de opciones de línea de comandos adicionales. Por ejemplo, para montar un proyecto de Vite + Vue, ejecute:
npm create vite@latest my-vue-app --template vue

cd my-project

npm install
npm run dev
