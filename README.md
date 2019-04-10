# Sample on providing CircleCI with a Docker image with a database in it

This repository contains a CircleCI configuration file that pulls
a custom MariaDB image that has a database installed in it.

It also has a Dockerfile that downloads a sample database
and installs it in a MariaDB image, following what
https://github.com/lindycoder/prepopulated-mysql-container-example does.
It is hosted at
https://cloud.docker.com/u/juampynr/repository/docker/juampynr/circleci-db.
