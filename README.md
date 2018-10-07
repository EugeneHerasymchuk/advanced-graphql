# All credits to [Scott Moss](https://github.com/hendrixer)

## Steps to run

* Install [Docker](https://www.docker.com/community-edition).
* Env file in the root folder
```shell
GITHUB_TOKEN=token_public_only
```
* Run mongo:

```shell
$ docker run -p 27017:27017 -d mongo
```

* Run project:
```shell
npm run dev
```



### tech check
* Node v8+
* Yarn / NPM (latest)
* Mongo (latest) (see below for Docker install)
* Git + Github

