
# Tools Install React JS

## 🚀 About React JS
The React Framework for Production Next.js gives you the best developer experience with all the features you need for production: hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more. No config needed.

## Install Vite React

 - [Vite](https://vitejs.dev/guide/)
 
```
npm create vite@latest nama-project -- --template react
```
- Install node.module
 ```
  npm install
 ```

## Formatter pritter code

```
npm install --save-dev --save-exact prettier
```

- Buat folder di root

```
.prettierrc.json
```

- Masukan isi .prittierrc.json

``` {
"tabWidth": 4,
"singleQuote": true,
"jsxSingleQuote": true,
"semi": true,
"printWidth": 150,
"bracketSpacing": true,
"braceSameLine": true
}

```

- command di terminal

```
npx prettier --write . 
```

- edit package json . di script tambahkan

``` 
"format": "prettier --write .", 
```

- untuk menjalankan di terminal

```
npm run format
```

## [Install Tailwind](https://tailwindcss.com/docs/guides/create-react-app)

- Ketik kode di terminal

```
npm install -D tailwindcss postcss autoprefixer
```

- Ketik di terminal 

``` 
npx tailwindcss init -p 
```

- copy script bawah ke tailwind.config.js ke isi content
```
content: [
"./index.html",
"./src/**/*.{js,ts,jsx,tsx}",
],

```
- copy script bawah ke index.css dan hapus semua isi sebelumnya dan hapus "app.css"
```
@tailwind base;
@tailwind components;
@tailwind utilities;

```

- kemudian import './index.css'; di main.js
```
import './index.css';
```
##  Running React JS with Tailwind

Install my-project with npm

```bash
  npm run dev
```

Install my-project with yarn

```bash
  yarn dev
```

- Untuk membuka di browser
```
http://localhost:5173/
```

## 🚀 About Me
Saya adalah seorang Front End Developer yang ingin terus belajar dan mengembangkan diri. Saya juga ingin berbagi ilmu yang saya dapatkan melalui tulisan di blog saya [lambangsasangka.com](https://lambangsasangka.com/).
    
![Logo](https://blog.logrocket.com/wp-content/uploads/2022/06/setting-up-dev-environment-react-vite-tailwind.png)


## Support

For support, email fake@lambangsasangka.com .

