
# Basic Redis Leaderboard Demo NodeJS

Show how the redis works with NodeJS, Express.

## Try it out

<p>
    <a href="https://heroku.com/deploy" target="_blank">
        <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heorku" width="200px"/>
    <a>
</p>

<p>
    <a href="https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fredis-developer%2Fbasic-redis-leaderboard-demo-nodejs&env=REDIS_ENDPOINT_URI,REDIS_PASSWORD&envDescription=REDIS_ENDPOINT_URI%20is%20required%20at%20least%20to%20connect%20to%20Redis%20clouding%20server" target="_blank">
        <img src="https://vercel.com/button" alt="Deploy with Vercel" width="200px" height="50px"/>
    </a>
</p>

<p>
    <a href="https://deploy.cloud.run" target="_blank">
        <img src="https://deploy.cloud.run/button.svg" alt="Run on Google Cloud" width="200px"/>
    </a>
</p>


## How it works?

<!-- ![How it works](docs/screenshot001.png) -->

## How to run it locally?

#### Copy `.env.sample` to create `.env`. And provide the values for environment variables

    - REDIS_ENDPOINT_URI: Redis server URI
    - REDIS_PASSWORD: Password to the server

#### Run frontend

```sh
cd client
npm run serve
```

#### Run backend

``` sh
npm start
```
