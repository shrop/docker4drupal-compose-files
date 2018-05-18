# Docker4Drupal Docker Compose files

These Docker Compose files are pulled from https://github.com/wodby/docker4drupal and modified with my custom changes. This makes it easier for me to keep up with these across projects and maintain my changes with new releases upstream.

Copy the docker compose file to the project root and make sure to rename it `docker-compose.yml`. Also, copy the .env file to the project root and edit variables as desired.

* `docker-compose.yml`
  * Docker4Drupal original Docker Composer file from https://github.com/wodby/docker4drupal
* `docker-composer-projectroot.yml`
  * For Drupal projects where the project root is also the html docroot.
  * Includes user-guided caching for improved Docker for Mac performance
  * Exposes port 3007 for MySQL access
* `docker-composer-docroot.yml`
  * For Drupal projects where there html docroot is `/docroot` below the project root.
  * Includes user-guided caching for improved Docker for Mac performance
  * Exposes port 3007 for MySQL access
* `docker-composer-web.yml`
  * For Drupal projects where the html docroot is `/web` below the project root.
  * Includes user-guided caching for improved Docker for Mac performance
  * Exposes port 3007 for MySQL access

[Docker4Drupal documentation](https://wodby.com/stacks/drupal/docs/local/quick-start/)