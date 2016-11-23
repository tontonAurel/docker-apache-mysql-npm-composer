FROM composer/composer:php5-alpine

WORKDIR /scripts

COPY ./docker/composer/entrypoint.sh /scripts

ENTRYPOINT ["/scripts/entrypoint.sh"]
