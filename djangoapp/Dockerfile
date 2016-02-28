FROM python:2.7

RUN apt-get update && \
  apt-get install -y \
  python-dev \
  libpq-dev \
  libjpeg-dev \
  libfreetype6-dev \
  zlib1g-dev \
  libpng12-dev \
  memcached

RUN mkdir /djangoapp
