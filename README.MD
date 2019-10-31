Webshop API
-----------

how to run migration?
1. run the mysql container
```bash
docker-compose up -d
```
2. run migrations
```bash
bin/console doctrine:migrations:migrate
```