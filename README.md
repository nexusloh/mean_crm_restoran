# RESTORAN CRM MEAN-stack
powered by
[![MEAN.JS Logo](http://meanjs.org/img/logo-small.png)](http://meanjs.org/)

[![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/dwyl/esta)

# Installation
```
git clone https://github.com/nexusloh/mean_crm_restoran.git
cd mean_crm_restoran
```
1. Перейти в `config/keys.dev.js` и вставте свою ссылку на вашу бд млаб в нужную строку
```
module.exports = {
    mongoURI: 'mongodb://login:password@ds119606.mlab.com:19606/namebd',
    mongoConfig: {
        useCreateIndex: true,
        useNewUrlParser: true
    },
    jwt: 'dev-jwt'
};
```
2. Установить пакеты проекта из корневой дериктории и `client`
3. Запустить срвер из корневой папки командой `npm run dev`
4. Запустить ангуляр из папки `client` командой `npm run start`
5. перейти на http://localhost:4200
demo: https://crmsystemds.herokuapp.com
