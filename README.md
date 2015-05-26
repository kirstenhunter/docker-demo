Docker Demo Repository
==========================

Demonstration repository for use when learning how to set up
docker containers for workshops.

To use, first install the code using git.  Follow the instructions
below to pull and prepare the system.

## Run the system locally
```
% git clone https://github.com/synedra/docker-demo.git
% cd docker-demo/webapp
% // Install pip if you don't have it already: https://pip.pypa.io/en/stable/installing.html
% sudo pip install --user -r requirements.txt 
% python app.py
```
Browse to localhost:3000

## Create your own github repository
Browse to http://www.github.com/synedra/docker-demo.git

Fork this repository as your own username

Copy the URL for your repository

## In the docker-demo directory do:
```
% git init
% git remote add origin <YOUR REPOSITORY URL>
% git remote -v
% git push origin master
```

## Create a docker container:
```
% cp Dockerfile-demo Dockerfile
% vi Dockerfile
```

Browse to hub.docker.com
Sign in with Github
"Add Repository" - Automated Build



To set the system up using Docker:
- install boot2docker
- 

## License

Apache 2.0

## Copyright

Copyright Kirsten Hunter <synedra@gmail.com>

