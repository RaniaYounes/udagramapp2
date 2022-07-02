pipeline consists of :

orbs
these are the required packeges to run every aspect of our workflow in this project 

jobs
the jobs are build and deploy.

workflow
 jobs will be done in it,  build job
  then we hold and wait for user's approval and then deploying the app.

the steps is

build:
build , install frontend and backend dependencies then lint frontend code then start building frontend and finally start building backend

hold:
  start deploying 

deploy:
by entering environment variables  install enviroment (node, AWS cli and EB cli ) then start deploying frontend and backend