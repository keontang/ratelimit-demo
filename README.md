# ratelimit-demo

Envoy proxy Rate Limit Service example.

## Usage

docker-compose up

```
ENVOY_CONFIG_FILE=http-rls.yaml docker-compose up

or

ENVOY_CONFIG_FILE=net-rls.yaml docker-compose up
```

docker-compose down

```
docker-compose down

or

docker-compose down --rmi 'all'
```

