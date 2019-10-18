# vuecli-uliweb-example

## Steps to init this project

Install [Vue Cli 3](https://cli.vuejs.org/zh/)

```
npm install -g @vue/cli
```

Create vue project

```
vue create vuecli-uliweb-example
```

Create back-end project

```
cd vuecli-uliweb-example
uliweb makeproject backend
```

## Directory structure

```
.
├── babel.config.js
├── backend //Uliweb back-end project
├── devproxy //Proxy for combine front-end and back-end dev servers
├── node_modules
├── package.json
├── package-lock.json
├── public
├── README.md
└── src
```



## Project setup

```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
