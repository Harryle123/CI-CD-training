# README

## Ruby version

- 3.0.4

## Rails version
- 6.1.7

## Requirements

- docker
- docker-compose

## Initial Setup

1. Change data of ```DATABASE_USER```, ```DATABASE_PASSWORD``` in ```.env``` to match your DB
2. Run command

```bash
$ docker compose build
$ docker compose run web rails db:create
```

## How to Develop

```bash
$ docker compose up
```

You can access `http://localhost:3000`.

## How to run the rails commands

```bash
$ docker compose run web xxx
```

## After update Gemfile or change setting file

```bash
$ docker compose build
```
