# Corratech OSS Wiki

This is the public-domain documentation website for CORRA Open Source Softwares.

## Projects

- [dkr-azure](https://github.com/corratech/dkr-azure)
- [dkr-capistrano](https://github.com/corratech/dkr-capistrano)
- [dkr-aws](https://github.com/corratech/dkr-aws)
- [dkr-make](https://github.com/corratech/dkr-make)

## dkr-azure

Docker Image for bootstrapping projects in Azure cloud.

This image contains:

- PHP Runtime
- Azure CLI
- dependencies

## dkr-capistrano

Docker Image used with capistrano deployments to bare metal linux boxes.

This image conatins:

- SSH Client
- Capistrano
- Terminal Notifier (Mac OS only)

## dkr-aws

Docker Image for bootstrapping projects in AWS Cloud.

This image contains

- Multiple PHP Runtime Versions
- Composer
- AWS CLI

## dkr-make

Docker Compose file for MariaDB, Adminer, Kibana and Elasticsearch.

This docker compose file contains:

- MariaDB
- Adminer
- Kibana
- Elasticsearch

Adminer is listening on 8080 port.
