ARG TAG='8.0.1-fpm-alpine3.12'
FROM arm32v6/php:${TAG}


COPY --from=arm32v6/composer /usr/bin/composer /usr/local/bin/composer


ARG TZ='Europe/Prague'

ENV DEFAULT_TZ ${TZ}

RUN apk add --no-cache libzip-dev zip
RUN docker-php-ext-install zip


#RUN mkdir tz
#COPY tzdata-2020f-r0.apk  tz
#RUN  cd tz && apk add --allow-untrusted tzdata-2020f-r0.apk
