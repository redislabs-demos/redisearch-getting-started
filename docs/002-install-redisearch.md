# Install RediSearch

You have multiple ways to run RediSearch:

* building from [sources](https://github.com/RediSearch/RediSearch) and installing it inside an existing Redis Instance
* using [Redis Cloud](https://redislabs.com/redis-enterprise-cloud/) _(when RediSearch module 2.0 available)_
* using [Redis Enterprise](https://redislabs.com/redis-enterprise-software/) _(when RediSearch module 2.0 available)_
* using [Docker](https://hub.docker.com/r/redislabs/redisearch/)

Let's use Docker for now.

**1.1 Open a terminal an run the following command**


```
> docker run -it --rm --name redis-search-2 \
   -p 6379:6379 \
   redislabs/redisearch:2.0.0
```

*Note: The container will automatically be removed when it exits (`--rm` parameter).*

You have now a Redis instance running with RediSearch installed, let's discover the basics.


---
Next: [Create Index](003-create-index.md)
