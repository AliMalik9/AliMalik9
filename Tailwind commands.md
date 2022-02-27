# We add this script in <head>
```bash
<script src="https://cdn.tailwindcss.com"></script>
```
```
npm init -y
```
For installing Tailwindcss with server
```
npm install -D tailwindcss postcss autoprefixer vite
```
```
npx tailwindcss init -p
```
Aad This script in package.json file
```
"start": "vite",
"build": "vite build"
```
Create style.css file and add this
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
For starting server
```
npm run start
```
Build Css For Production (Deployment)
```
npm run build
```
You can see the TailwindCss full file and customize the config file 
```
npx tailwindcss init NAME --full
```
