# dockerfiles

## Usage (example)

### docker  
php build:
```sh
$ docker build -t php:ilaocai -f php_Dockerfile .
```
php container:
```sh
$ docker run -idt -p 80:80 -v /data:/var/www/html php:ilaocai
```

### dockercompose
```sh
$ docker-compose -f composefiles/php.yml up -d
```