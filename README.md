## Recipes Challenge

This project use:

[NestJs](https://github.com/nestjs/nest){:target="\_blank"} - Backend: NestJS is a framework for building efficient, scalable Node.js web applications. It uses modern JavaScript

[NextJs v13](https://nextjs.org/blog/next-13){:target="\_blank"} - Frontend: This use NextJs 12 project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app){:target="\_blank"}.

This project use experimental `app` directory of Next13

[PostgreSQL](https://www.postgresql.org){:target="\_blank"} - PostgreSQL is a powerful, open source object-relational database system with over 35 years of active development that has earned it a strong reputation

[TypeORM](https://typeorm.io/){:target="\_blank"} - TypeORM is an ORM that can run in NodeJS

[Node.js](https://nodejs.org/en/){:target="\_blank"} - Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

[Docker](https://docker.com){:target="\_blank"} - Docker is a platform designed to help developers build, share, and run modern applications. We handle the tedious setup, so you can focus on the code.

[Redis](https://redis.io/){:target="\_blank"} - Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker.

[TheMealDB](https://www.themealdb.com/){:target="\_blank"} - This is a public database of recipes, I take this recipes and fill out my local database. Including images and thumbnails

## Installation

To run the project you need to install [docker](https://docs.docker.com){:target="\_blank"}, and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git){:target="\_blank"} you can follow the instructions below

- [How to install on mac](https://docs.docker.com/desktop/install/mac-install/){:target="\_blank"}
- [How to install on windows](https://docs.docker.com/desktop/install/windows-install/){:target="\_blank"}
- [How to install on linux](https://docs.docker.com/desktop/install/linux-install/){:target="\_blank"}
- [How to install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git){:target="\_blank"}

Once you have docker installed, and running in your local environment, you can clone this repository and start the docker containers

```bash
$ git clone https://github.com/ecasanova/recipes-challenge.git
$ cd recipes-challenge
$ docker compose up -d
```

## Usage

You can see the backend in: [http://127.0.0.1:3005/api](http://127.0.0.1:3005/api){:target="\_blank"}

You can see the frontend in: [http://127.0.0.1:8080](http://127.0.0.1:8080){:target="\_blank"}

You can see redis commander in [http://127.0.0.1:8081/](http://127.0.0.1:8081/){:target="\_blank"}

PostgreSQL database is running on the port 5432

Redis instance is running on the port 6379

## Support

Enrique Casanova - [ecasanova@webfactorystudio.co](ecasanova@webfactorystudio.co)

## Overview

A public database was used for the initial loading of the system, this information was loaded into the PostgreSQL database, and the project includes migrations at startup

## Database Structure

This is the structure of the database:

![ER](backend/static/recipes-er.png)
