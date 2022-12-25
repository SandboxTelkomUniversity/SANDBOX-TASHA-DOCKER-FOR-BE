# SANDBOX-TASHA-DOCKER-FOR-BE
> Docker Only for Backend Engineer

# Mongo Uri
- Download MongoDB Compass or Robo 3T: studio 3T
- Insert the uri to connect
`mongodb://tasha-dev:<password>@localhost:27017/?authMechanism=DEFAULT&authSource=admin`

# Postgres Uri
- Download pgAdmin4 or DBeaver
- Insert the uri to connect
`postgresql://tasha-dev:<password>@localhost:5432/postgres?sslmode=disable`

# Redis connection
- Open terminal or cmd or iTerm
- Insert the command
`docker exec -it sandbox-tasha-docker-for-be-redis-1 redis-cli`

# Kafka connection
- following the docker-compose.yml configuration
- can test using Kafkatool: Offset Explorer 2