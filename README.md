# php8-oci-docker
Docker-compose with PHP 7.4 &amp; OCI Extensions, Apache 2.4

## Apache
**Version:** 2.4.38

## PHP
**Version:** 7.4

**Extensions enabled:** OCI & MySQL
#### If you need more PHP extensions, change the `php/Dockerfile` file and restart the containers

## Quick Start

#### Clone the repository:
`git clone https://github.com/lekomtsev/php-oci-docker`

#### Go to the root folder:
`cd php-oci-docker`

#### Start the environment:
`docker-compose up -d`

#### Open your browser and go to:
`http://localhost:3333`

#### That's it 🎉

## Other info

#### SSH into the PHP & Apache container
`docker-compose exec app bash`

#### Change Apache port
- Change 3333 value in `docker-compose.yml` file

#### Based
    https://github.com/samuel27m/php8-oci-docker
