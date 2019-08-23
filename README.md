# jwt-laravel
Laravel Project on Docker with JWT integration

You will need these installed on your system.

- Docker
- Docker Compose


Clone the repository.

Go to the project directory and run the command 

```bash
docker-compose up --build
```

Get access to the containers bash with testuser and run all the necessary artisan commands

```bash
docker exec -ti -u testuser jwt-laravel_app_1 bash
```

To get details explanation on how to integrate JWT authentication in yout Laravel project you can read this [article on medium](https://medium.com/monstar-lab-bangladesh-engineering/jwt-authentication-in-a-laravel-project-787fe9b1e179)

To get details explanation on how to setup/create your own Laravel project on Docker you can read this [article on medium](https://medium.com/monstar-lab-bangladesh-engineering/boot-a-laravel-project-on-docker-72501d3487e1)
