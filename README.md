# hackernews-async-ts
前端模块化学习demo
[Hacker News](https://news.ycombinator.com/) showcase using typescript && egg

## QuickStart

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

### Deploy

```bash
$ npm run tsc
$ npm start
```

### Npm Scripts

- Use `npm run lint` to check code style
- Use `npm test` to run unit test
- se `npm run clean` to clean compiled js at development mode once

### Requirement

- Node.js 8.x
- Typescript 2.8+

## docker使用

### 镜像生成
```bash
$ docker image build -t module-study .
```

### 运行docker容器
```bash
$ docker container run -p 7001:7001 module-study
$ open http://localhost:7001/
```