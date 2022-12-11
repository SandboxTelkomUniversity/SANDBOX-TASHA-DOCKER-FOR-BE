# SANDBOX-TASHA-DOCKER-FOR-BE
> Docker Only for Backend Engineer

## Requirements
1. Docker version 18.06.1-ce
2. Docker-compose version 1.22.0

## Usage

Before running docker-compose, please make sure you stop every brew services. 

Run this command : 

```shell
// list of running service
brew services list

// stop redis
brew services stop redis

etc
```


Run using docker-compose :

```shell
// running docker
docker-compose up -d

// checking running docker
docker ps

// checking docker value
docker volume ls

// stop docker
docker-compose stop

// destroy docker
docker-compose down
```

## Notes

When running first time, you will get multiple errors when start kafka. Don't worry, it just your connection not fast enough. Use your lan cable :) .
For kafka, you need add KAFKA_ADVERTISED_HOST_NAME to /etc/hosts

```shell
127.0.0.1	localhost kafka.docker
```

## Contributing

Want to contribute ? Just pull request to master.

## Licensing

"The code in this project is licensed under Tasha Development Team license."