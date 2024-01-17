FROM python:3.10.0

# Installation des dépendances système
RUN apt-get update && apt-get install -y \
    python3-dev \
    libxml2-dev libxslt1-dev zlib1g-dev \
    libsasl2-dev libldap2-dev \
    build-essential libssl-dev libffi-dev \
    default-libmysqlclient-dev libjpeg-dev libpq-dev libjpeg62-turbo-dev \
    liblcms2-dev libblas-dev libatlas-base-dev \
    gcc

# Mise à jour de pip
RUN pip install wheel setuptools pip --upgrade
RUN pip3 install wheel setuptools pip --upgrade