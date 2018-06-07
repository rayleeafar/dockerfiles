FROM ubuntu:16.04
ENV PYTHONUNBUFFERED 1

RUN apt-get update && apt-get install -y \
  build-essential \
  python3 \
  python3-pip \
  python3-dev \
  git-core \
  libpq-dev \
  libjpeg-dev \
  binutils \
  libproj-dev \
  gdal-bin \
  libxml2-dev \
  libxslt1-dev \
  zlib1g-dev \
  libffi-dev \
  libssl-dev \
  language-pack-pt\
  python3-gdal\
  byobu\
  sudo\
  vim\
  && rm -rf /var/lib/apt/lists/* 
RUN pip3 install shapely\   
                 mgrs\
                 pendulum\
                 pyaml\
                 requests\
                 dicttoxml\
                 joblib\
                 pillow\
                 pika\
                 arrow\
                 psycopg2-binary\
    && pip3 install --no-cache-dir matplotlib sqlalchemy\
    && rm -rf /root/.cache/
