# OpenAPI Specification and KrakendD API Gateway

## KrakenD API Gateway

```sh
docker run -p "8080:8080" --name krakend-development -v ${PWD}/config/krakend:/etc/krakend/ devopsfaith/krakend run -c krakend.json
```

```curl
http://localhost:8080/__health
```
