# Docker4Drupal Docker Compose files

These Docker Compose files are pulled from https://github.com/wodby/docker4drupal and modified with my custom changes. This makes it easier for me to keep up with these across projects and maintain my changes with new releases upstream.

Copy the docker compose file to the project and make sure it is named `docker-compose.yml`.

* `docker-compose.yml`
  * Docker4Drupal original Docker Composer file from https://github.com/wodby/docker4drupal
* `docker-composer-drupal-project.yml`
  * For Drupal 8 [Drupal Project](https://github.com/drupal-composer/drupal-project) with docroot in `/web`
  * Exposes port 3007 for MySQL access
* `docker-composer-drupal-root.yml`
  * For Drupal 7 and 8 project where the docroot is `./`
  * Exposes port 3007 for MySQL access

[Docker4Druapl documentation](https://docker4drupal.readthedocs.io/en/latest/)