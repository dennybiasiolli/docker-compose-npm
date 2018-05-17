# docker-compose-npm

A docker-compose system with Nginx, PHP and MySQL


#### Initialize project

- Clone repository and enter it

- Create a `.env` file starting from [`.env.sample`](.env.sample)

    `cp .env.sample .env`

- Launch with `docker-compose up`


#### Services

MySQL is accessible on localhost at port 3306, default root password
can be found in the `.env` file.

After environment launch, open http://127.0.0.1/ to access web content.

PhpMyAdmin can be found at http://127.0.0.1:8080/.

Place your weh content in `html` directory, will be processed by Nginx/PHP.
