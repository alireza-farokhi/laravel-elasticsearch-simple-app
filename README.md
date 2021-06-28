# laravel-elasticsearch-simple-app
its a simple demo of using elastic search in laravel

## docker
- `./vendor/bin/sail up -d`
### first of all, enter into the container using:
- `./vendor/bin/sail exec laravel.test bash`

### feel free to install dependecies
- `scp .env.example .env`
    - put this lines to your env file
        - `FORWARD_DB_PORT=33060`
        - `APP_PORT=8000`
        - `ELASTICSEARCH_ENABLED=true`
        - `ELASTICSEARCH_HOSTS="http://elasticsearch:9200"`
- `composer install`
- `npm install`
- `npm run dev`
- `php artisan migrate --seed`

## enjoy searching on 127.0.0.1:8000

