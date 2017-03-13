# Installation

- Run `docker-compose pull` to pull all container images.
- Run `docker-compose up -d` to start the web server.
- Go to [http://localhost/](http://localhost/) in a browser. You should see the homepage of the meetup application.

# Running development tools

- `bin/run_tests.sh` to run all the tests
- `bin/composer.sh` to use Composer to install extra packages, etc.
- `bin/deptrac.sh` to analyze dependencies

# XDebug & PhpStorm

Follow [these instructions](https://github.com/matthiasnoback/php-workshop-tools#setting-up-xdebug-with-phpstorm) to get it working.