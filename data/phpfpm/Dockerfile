FROM php:7-fpm-alpine
RUN set -x && \
  apk add --no-cache icu-libs && \
  apk add --no-cache --virtual build-dependencies icu-dev && \
  NPROC=$(grep -c ^processor /proc/cpuinfo 2>/dev/null || 1) && \
  docker-php-ext-install -j${NPROC} intl && \
  apk del --no-cache --purge build-dependencies && \
  rm -rf /tmp/pear
