# project

## prereq
 - npm
 - node
 - docker
 
 ## install 
 Pull this repository and run `git submodule update --init --recursive` to pull submodules

## running

To run this project, set correct .env file, and run this command `docker-compose --env-file up --build`

We are using github submodules, both frontend and backend are in different repositories linked to this 'master' repository.
We are using postgres as database, redis - for caching requests, node+express on backend, and react with mui on frontend
