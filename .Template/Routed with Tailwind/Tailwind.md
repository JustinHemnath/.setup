### npm install

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
npm i react-router-dom

npm i daisyui
npm i flowbite flowbite-react


### Paste IN 'tailwind.config.js'

/** @type {import('tailwindcss').Config} */ 
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

### Paste in 'index.css' or 'App.css'


@tailwind base;
@tailwind components;
@tailwind utilities;

---------------DONE------------






### FOR FLOWBITE-REACT, follow the above but paste the following in tailwind.config.js

module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
    'node_modules/flowbite-react/**/*.{js,jsx,ts,tsx}'
  ],
  theme: {
    extend: {},
  },
  plugins: [
      require('flowbite/plugin')  
    ],
}