# Docker Compose with MySQL, Adminer, and PHP/Apache

Clone repo and run:

```
npm run init
```

Create a `.env` file and customize the contents:

```
MYSQL_USER=user
MYSQL_PASSWORD=pass
MYSQL_DATABASE=my_db
MYSQL_ROOT_PASSWORD=root_pass
```

Put any `.sql` files you want to initialize the database with in the `init` directory.

Put any PHP files in the `php` directory.

Run `npm start` or `docker-compose up -d` to launch all services.

Access the Adminer UI at `http://localhost:8080`, and PHP over `http://localhost`.
