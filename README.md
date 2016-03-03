Crusca-Nginx
============

This is a setup to run Nginx in front of [Crusca](https://github.com/riquito/crusca).

Requires [docker-compose](https://github.com/docker/compose) >= 1.6.0

### Setup

Copy `crusca.yml.dist` to `crusca.yml` and configure it to your liking.

See [crusca documentation](https://github.com/riquito/crusca) for configuration options.

Copy `nginx.conf.template.dist` to `nginx.conf.template`, it should be already good as it is.

### Run

    CRUSCA_NGINX_SERVER_NAME=crusca.yourdomain.com docker-compose up
