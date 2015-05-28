Docker Demo Repository
==========================

Demonstration repository for use when learning how to set up
docker containers for workshops.

## Create your own github repository
Browse to http://www.github.com/synedra/docker-demo.git

On github, Fork this repository to your own username

Copy the URL for your repository

## In the docker-demo directory in your local clone do:
```
% git init
% git remote add origin <YOUR REPOSITORY URL>
% git remote -v
% git push origin master
```

In a browser, browse to http://hub.docker.com
Sign in with Github
"Add Repository" - Automated Build
Select the repository that you just created
The build will start - it will show up as "pending", it could finish in a few minutes or several hours

To set the system up on Windows or Macintosh using Docker:
- install boot2docker
- boot2docker init
- boot2docker start
- boot2docker init <returns boot2docker IP>
// Set environment variables as directed
- docker run -i -t -p 80:3000 <username>/docker-demo /bin/bash
# node toppings.js
Browse to <boot2docker IP> 

There, you've created your own docker container.  All you need is the Dockerfile to tell the system how to build, and any changes you make to the git respository will kick off a new build in docker.

## License

Apache 2.0

## Copyright

Copyright Kirsten Hunter <synedra@gmail.com>

