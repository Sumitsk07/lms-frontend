# LMS Frontend

### Setup instruction

1. Clone the project

```
    git clone https://github.com/Sumitsk07/lms-frontend.git
```

2. Move into the directory

```
    cd lms-frontend
```

3. install dependencies

```
    npm i
```

4. run the server

```
    npm run dev
```

### Setup instructions for tailwind

[Tail wind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindcss

```
    npm install -D tailwindcss
```

2. Create tailwind config file

```
    npx tailwindcss init
```

3. Add file extensions to tailwind config file in the contents property

```
    "./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add the tailwind directives at the top of the `index.css` file

```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```

### Adding plugins and dependencies

```
npm install @reduxjs/toolkit@1.9.5
npm install react-redux@8.1.2
npm install react-router-dom@6.15.0
npm install react-icons@4.10.1
npm install react-chartjs-2@5.2.0
npm install chart.js@4.4.0
npm install daisyui@3.6.3
npm install axios@1.5.0
npm install react-hot-toast@2.4.1
npm install @tailwindcss/line-clamp@0.4.4
```
