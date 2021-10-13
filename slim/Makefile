# Slimのインストール
install:
	docker-compose exec php composer require slim/slim:"4.*"
	docker-compose exec php composer require slim/psr7
	docker-compose exec php composer require nyholm/psr7 nyholm/psr7-server
	docker-compose exec php composer require guzzlehttp/psr7 http-interop/http-factory-guzzle
	docker-compose exec php composer require laminas/laminas-diactoros
	mkdir public && touch index.php
	cat index.php.tmp > public/index.php


