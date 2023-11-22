para inicializar el server agregamos en el package.json el dev:

```
"scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "dev": "node --watch ./server/index.js"
    },
```

y en consola simplemente el:

```
npm run dev
```
