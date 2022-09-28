# Database Playground

This repo serves as a place to toy with different databases, and their
associated UI interfaces.

### Ports

| Port | Database |
|------|----------|
| 8081 | redis-commander |
| 8082 | pgAdmin |
| 8083 | mongo-express |
| 8084 | adminer |

You can connect to any of these using their respective 
connection strings in any given language.
For example, a connection string for postgres would look like  
`postgresql://{username}:{password}@{endpoint}/{database}`  
or in this example  
`postgresql://admin:pass@localhost:5432/mydb`  
or, if accessing from inside another docker container  
`postgresql://admin:pass@postgres:5432/mydb`  

Info on each container can be found at the following links:
[Docker Mysql Image](https://hub.docker.com/_/mysql)  
[Docker Postgres Image](https://hub.docker.com/_/postgres)  
[Docker Mongodb Image](https://hub.docker.com/_/mongo)  
[Docker Redis Image](https://hub.docker.com/_/redis)  
  
[Postgres connector](https://www.postgresqltutorial.com/postgresql-python/connect/)  
[Mongodb tutorial](https://www.freecodecamp.org/news/learn-mongodb-a4ce205e7739/)  

