# koa-typescript-with-db

An extension of the [koa-typescript-template](https://github.com/alanbueno/koa-typescript-template)

koa-template is a basic Restful API template build on top of koa.js v2 framework.

## Ready, set, go!

Download the dependencies, create your SentryProject on [https://sentry.io/](https://sentry.io/), and run, just like that!

Clone the repo:
`https://github.com/alanbueno/koa-typescript-with-db`

Run `npm install` or `yarn install`

[Set your .env variables](https://github.com/alanbueno/koa-typescript-with-db#env-variables)

Run `npm start` or `yarn run start`

## Env Variables

Set the env variables (optional\*\*)

```shell
SENTRY_URL=someTokenYouAlreadyCreatedOnSentryPage@sentry.io/someNumber
```

## Usage

Once the app is ready n running, use any HTTP(s) client to make a request::

You can set port on config file, if not, default is 3001.

Example: http://localhost:3001/

- Method: GET
- Host: http://localhost:3001
- Path: '/'

Should return just:

```
{
  "version":"0.0.1",
  "uptime":9.567
}
```

---

Example: http://localhost:3001/ping

- Method: GET
- Host: http://localhost:3001
- Path: '/ping'

Health Check should return just:

```
pong
```

---

Example: http://localhost:3001/somePost

- Method: GET
- Host: http://localhost:3001
- Path: '/somePost'

Post should return just:

```
{
    "first": "Test",
    "second": "Another test",
    "number": 1,
    "flag": true
}
```
