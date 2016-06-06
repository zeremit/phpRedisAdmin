[phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin.git)  1.6.0 for Cloud foundry
========================================================================================



phpRedisAdmin is a simple web interface to manage [Redis](http://redis.io/) databases.

### Usage

1. Clone the app (i.e. this repo).

  ```
  git clone https://github.com/zeremit/phpRedisAdmin-cf-deploy
  cd phpRedisAdmin-cf-deploy
  ```

1. Edit the manifest.yml file.  Change the 'name','host','port','auth' attribute to something unique.

1. Push it to CloudFoundry.

  ```
    cf push
  ```
