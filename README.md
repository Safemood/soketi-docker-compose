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
