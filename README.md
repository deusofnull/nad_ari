build guide:

here are the commands you have to run, in order, to build this project.

1 - git clone "this project url"

2 - composer create-project laravel/laravel ari 5.2.*

3 - docker-compose build

4 - docker-compose up

5- // check to see that docker-compose up isnt throwing any crazy errors

6 - ctrl-c // to turn off the current docker containers running the application

7 - docker-compose up -d // run the containers in daemon mode, aka in the background.

Notes:


*2 We want to install laravel 5.2, not the most recent.  Using the CLI app
laravel new "project name" would install the latest laravel, meaning 5.4 in may 2017.
We want 5.2, so we use the composer create-project method instead
https://laradevtips.com/2016/08/24/how-to-install-laravel-application-5-and-4/
