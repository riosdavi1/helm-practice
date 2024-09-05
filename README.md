# helm-practice

## Build

```
mvn clean install
docker-compose build
docker-compose up -d
```

## Run

To run service and client:

```
docker-compose up -d
```

To run only the service:

```
docker-compose up -d --scale thrift-service=1 --scale thrift-client=0
```

To lunch the client:

```
docker-compose up -d --scale thrift-service=1 --scale thrift-client=1
```
