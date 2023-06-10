# 3D-TeeLab

<h1> Set Up </h1>

We are building this application by using Vite (Building Tool).

Vite is a fast and opinionated build tool and development server for modern web applications. It was developed with a focus on providing a streamlined and efficient development experience. Vite is particularly popular in the JavaScript ecosystem, often used with frameworks like Vue.js and React.

<h2> Create a new Vite Project </h2>

```
npm create vite@latest -- --template react client
```

<h2> Add the required dependencies</h2>

```
npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion
```

<h2>Install Tailwind CSS </h2> 

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

<h2> Configure your template paths in your tailwind.config.js file.</h2>

```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

<h2>Add the Tailwind directives to your CSS
Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.</h2>

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

