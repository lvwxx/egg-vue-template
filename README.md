# egg-vue-template

A template of eggjs and vue project

## Explain

开发时 前端路由中 /api 开头的将会代理到 localhost:7001端口

## QuickStart


<!-- add docs here for user -->

see [egg docs][egg] for more detail.

### Development

## Server
```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

## Frontend
```bash
$ cd front-end
$ npm i 
$ npm run dev
$ open http://localhost:8080
```

### Deploy 

```bash
$ cd front-end
$ npm run build // index.nj and js、css will build public or view file
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.


[egg]: https://eggjs.org