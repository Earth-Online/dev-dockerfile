
FROM webdevops/php-apache-dev:ubuntu-15.10
LABEL maintainer="linlanxi7552659@gmail.com"
ONBUILD COPY --chown=application:application .  /var/www/html
ONBUILD ENV WEB_DOCUMENT_ROOT /var/www/html
