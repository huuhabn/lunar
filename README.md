## Installation with Docker

> Make sure you have Docker installed on your local machine.

```bash
cp .env.docker.example .env
docker-compose up
```

### Environment Demo store

You can execute it via the `docker compose up` command in your favorite terminal. 
Please note that the speed of building images and initializing containers depends on your local machine and internet connection - it may take some time. 

```bash
cp .env.example .env
```

Install Lunar
```bash
php artisan lunar:install
```

Seed the demo data.
```bash
php artisan db:seed
```

Link the storage directory
```bash
php artisan storage:link
```

Start serve

```bash
php artisan serve --port=8010
```
The demo store will be available to `http://127.0.0.1:8010` in your browser.

####  Log into Lunar panel

Once the project is prepared, the Lunar panel will start and available to `http://127.0.0.1:8010/lunar`. 

