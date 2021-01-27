# Sample Nestjs + Docker containers + Heroku Deploy

##### Content:

- <b>[nestjs-heroku-sample1](https://nxe-api1.herokuapp.com):</b>
  nestjs api to provide basic resources for other apis
  [https://nxe-api1.herokuapp.com](https://nxe-api1.herokuapp.com)
- <b>[nest-js-heroku-sample2](https://nxe-api2.herokuapp.com):</b>
  nestjs api to access nestjs-heroku-sample1, calculate service and return data
  [https://nxe-api2.herokuapp.com](https://nxe-api1.herokuapp.com)

##### Dependenicies:

- Docker version 19.03.12, build 48a66213fe

##### Run:

1.  clone the repo and the api submodules.

```

 git clone https://github.com/Badaueba/backend-challenge.git

 cd backend-challenge

 git submodule init

 git submodule update

```

2. Install yarn dependencies for the microservices

```

cd nest-js-heroku-sample2
yarn install

cd nestjs-heroku-sample1
yarn install

```

3 . Start the workspace containers

```
docker-compose up --build

```

4 . Open up your web browser at localhost:3000
