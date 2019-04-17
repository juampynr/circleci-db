# Custom Docker image that has a MariaDB in it

Find out the story behind this repository at [this Lullabot article](https://www.lullabot.com/articles/rocket-ship-fast-jobs-circleci-preinstalling-database).

This repository contains a CircleCI configuration file that pulls
a custom MariaDB image that has a database installed in it.

The custom image used by CircleCI is built at Docker Hub by the
Dockerfile located in this repository.

Links:

* [Lullabot article](https://www.lullabot.com/articles/rocket-ship-fast-jobs-circleci-preinstalling-database)
* Based on https://github.com/lindycoder/prepopulated-mysql-container-example.
* Docker hub repository that [hosts the custom image](https://cloud.docker.com/u/juampynr/repository/docker/juampynr/circleci-db).
