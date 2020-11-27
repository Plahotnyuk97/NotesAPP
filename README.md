
{
  "name": "NotesApp",
  "version": "0.0.1",
  "description": "Notes application",
  "scripts": {
    "server": "babel-node server/app.js"
  },
  "author": {
    "name": "Vadim",
    "email": "vadimplahotnk@gmail.com",
    "url": "https://github.com/Plahotnyuk97"
  },
  "dependencies": {
    "body-parser": "*",
    "cors": "*",
    "express": "*",
    "mongoose": "*"
  },
  "devDependencies": {
    "babel": "5.x",
    "babel-loader": "5.x"
  }
}


### Запуск проекта

1. Clone this repo
2. `cd spa-webinar`
3. `npm install`
4. Скопируйте `etc/config.js.sample` в `etc/config.js`
4. `npm run server`
5. `npm run webpack-devserver`
6. Откройте http://localhost:8090 в браузере
