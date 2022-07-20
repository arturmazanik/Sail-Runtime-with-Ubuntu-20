# New configuration with downgrade Ubuntu version to 20.04
## laravel sail with ubuntu 20
### It is not custom sail version! It's only config Dockerfile with other Ubuntu version.

### Install from composer:
```
  composer require arturmazanik/sail8.1-with-ubuntu20-without-pgsl
```

### After installing add context in laravel.test:

```
  context: ./vendor/arturmazanik/sail8.1-with-ubuntu20-without-pgsl/runtimes/8.1
```

### OR for local env

```
    context: ./vendor/arturmazanik/sail8.1-with-ubuntu20-without-pgsl/runtimes/8.1-local
```
