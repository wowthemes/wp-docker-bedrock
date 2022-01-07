FROM johnpbloch/phpfpm:7.1

# Install OS utilities
RUN apt-get update
RUN apt-get -y install \
    curl \
    iputils-ping \
    net-tools \
    git \
    zip \
    unzip \
    wget \
    vim

CMD ["php-fpm"]

