# symfony5-boilerplate

### features

- login
- register
- simple theme
- user profile
- docker

## run

#### Clone the repo
`clone git@github.com:smoqadam/symfony5-boilerplate.git`

#### Run docker

`docker-compose up` 

#### run migrations

`docker exec -it symfony5-boilerplate_php_1 bash` 

Note: change the container name

```bash
bin/console make:migration
bin/console doctrine:migrations:migrate
```

#### Open http://localhost:8008



