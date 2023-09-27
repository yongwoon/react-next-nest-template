# How to create project ?

## common

- Create Network (only one time)

```bash
docker network create dev_next_nest_template_network
```

## Create Nestjs Project (Backend)

- Create Project

```bash
docker-compose run --rm backend nest generate application
```

## Create Nextjs Project (Frontend)

- Create Project

```bash
docker-compose run --rm frontend npx create-next-app@latest --ts --use-npm
```

- 一個上の directory (app) に作成された file をすべて移動
- `src` directory 作成
- `src` directory に `page`, `styles` directory を入れる
