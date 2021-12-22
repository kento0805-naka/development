init:
	docker-compose up -d --build
	docker-compose exec app composer create-project --prefer-dist "laravel/laravel=8.*" .
	cp .env.example ./src/.env
	docker-compose exec app php artisan migrate
	docker-compose exec app php artisan key:generate
	