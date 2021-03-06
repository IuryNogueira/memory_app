# Read Me

1. start containers in background (only use images)

   `docker-compose up -d`

1. config db

   `docker-compose exec memory_app_back rake db:create db:migrate db:seed`

1. tests backend unit

   `docker-compose exec memory_app_back rspec`


1. tests frontend e2e

   `docker-compose up -d memory_app_e2e`

1. access

   `http://localhost:8080`

1. Semaphore (parallel tests / lint)

   [![Build Status](https://edimossilva.semaphoreci.com/badges/memory_app/branches/master.svg?style=shields)](https://edimossilva.semaphoreci.com/projects/memory_app)

1. Code-climate - Test Coverage

   [![Test Coverage](https://api.codeclimate.com/v1/badges/acf7bd7bd4f5d1a4e7bc/test_coverage)](https://codeclimate.com/github/edimossilva/memory_app/test_coverage)

1. Code-climate - Maintainability

   [![Maintainability](https://api.codeclimate.com/v1/badges/acf7bd7bd4f5d1a4e7bc/maintainability)](https://codeclimate.com/github/edimossilva/memory_app/maintainability)

1. Heroku

   https://memory-app-back.herokuapp.com/

1. Swagger

   https://memory-app-back.herokuapp.com/api-docs/index.html

1. Docker image

   https://hub.docker.com/repository/docker/edimossilva/memory_app_rails
   https://hub.docker.com/repository/docker/edimossilva/memory_app_vue
   https://hub.docker.com/repository/docker/edimossilva/memory_e2e
