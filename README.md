# Fullstack Developer Test

## Admin Users App

This is a responsive application to manage users done as a test for Umanni hiring process.

## Requirements
* Ruby 3.1.2
* Rails 7.0.4
* PostgreSql 10+
* Docker and Docker Compose v2

## Initial setup
```bash
git clone https://github.com/JacquesMarques/user-admin-umanni.git
cd Fullstack-Developer
cp .env.example .env
docker-compose build
docker compose run --rm web bin/rails db:setup
```

## Start Rails App
```bash
docker compose up
```

## Running tests
```bash
docker compose run --rm web bin/rspec
```

