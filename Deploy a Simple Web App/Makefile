build:
	docker build -t simple-web .

run:
	docker run -d --name simple-web -p 8080:80 simple-web

stop:
	docker stop simple-web

restart: stop build run

