# IntraLite
A small intranet designed to show useful information to someone. IE links and noticeboard(s). 

### Roadmap
* Noticeboard
* Move API to .netCore (??)

### Tooling
NodeJS, VueJS, PostgreSQL


## Setup Config
You should just be able to rename the `config.tpl.js` to `config.js` and populate the detail.

You will also need to create the PSQL database, which can be found `\documentation\sql\createtable.sql`

## Install on Windows IIS Server
In the `documentation` directory you will see the WindowService.js.

```
npm i node-windows
node documentation/WindowService.js
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

