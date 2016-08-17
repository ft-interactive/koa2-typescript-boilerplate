# Koa 2 TypeScript boilerplate

This is a quick boilerplate instructing how configure TypeScript to work with Koa et al.

## To use:

1. Clone:

  `$ git clone https://github.com/ft-interactive/koa2-typescript-boilerplate.git`

2. `npm` install:

  `$ cd koa2-typescript-boilerplate && npm install`

  This will also install the TypeScript definitions used in this project.

3. To run the development server, run:

  `$ npm run dev-server`

  This uses `ts-node` to transpile on-the-fly and probably ain't the best idea for production.

4. To build for production, run:

  `$ npm run build`

  ... Which can then be started with:

  `$ npm start`

  Included is a Procfile that will do this for you on Heroku.

## ToDo:
- [ ] Add some basic SuperTest integration tests
- [ ] Add an example using `koa-views` or somesuch
- [ ] Write some example middleware showcasing async/await hawtness
