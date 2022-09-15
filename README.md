# README

## Ruby version

- 3.1.2

## Rails version
- 7.0.4

## Requirements

- Docker
- docker-compose

## Initial Setup

```bash
$ docker-compose build
$ docker-compose run web rails db:create
```

## How to Develop

```bash
$ docker-compose up
```

You can access `http://localhost:3000`.

## How to run the rails commands

```bash
$ docker-compose run web xxx
```

## After update Gemfile

```bash
$ docker-compose build
```
