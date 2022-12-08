# Simple docker-compose to run soketi WebSockets server.

## **update environment variables**

```js
SOKETI_PORT=6001
SOKETI_METRICS_SERVER_PORT=9601
DEBUG=1
PUSHER_APP_ID=app-id
PUSHER_APP_KEY=app-key
PUSHER_APP_SECRET=app-secret
PUSHER_HOST=127.0.0.1
PUSHER_PORT=6001
PUSHER_SCHEME=http
DEFAULT_APP_ENABLE_CLIENT_MESSAGES=false # make true if you want to enable client events
```

## **Run Soketi server**

```js
docker-compose up -d
```

## one line

```js
docker run -p 6001:6001 -p 9601:9601 -e DEFAULT_APP_ID=some-id -e DEFAULT_APP_KEY=some-key -e DEFAULT_APP_SECRET=some-secret quay.io/soketi/soketi:0.17-16-alpine
```

## https://kbouzidi.com

### you can check the related article <a href="https://kbouzidi.com/real-time-events-with-laravel-and-soketi">REAL-TIME EVENTS BROADCASTING WITH LARAVEL 9 & SOKETI

</a>
