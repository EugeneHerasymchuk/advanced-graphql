# All credits to [Scott Moss](https://github.com/hendrixer)

## Steps to run

* Install [Docker](https://www.docker.com/community-edition).
1) Created .env file in the root folder with this content.
```shell
GITHUB_TOKEN=token_public_only
```
 The token you can generate, following next steps:
![image](https://user-images.githubusercontent.com/16426867/46601983-303b7e80-caef-11e8-8342-d8e711af0e6b.png)

![image](https://user-images.githubusercontent.com/16426867/46602048-67119480-caef-11e8-8fc3-118dbe092728.png)

![image](https://user-images.githubusercontent.com/16426867/46602103-87415380-caef-11e8-90f8-db4e4d9ff326.png)


2) Run mongo:

```shell
$ docker run -p 27017:27017 -d mongo
```

3) Run project and face the error :) :
```shell
npm run dev
```



### tech check
* Node v8+
* Yarn / NPM (latest)
* Mongo (latest) (see below for Docker install)
* Git + Github

