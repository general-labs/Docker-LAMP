# Docker LAMP Starter Kit
 Basic LAMP starter kit. 


### Installation
Uncomment the following line in `docker-compose.yml` if you want to seed the database.
`- ./resources/mysql/seed/news.sql:/docker-entrypoint-initdb.d/news.sql`

```
docker-compose up -d
```

Visit `http://localhost:8100`