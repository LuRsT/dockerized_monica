# Dockerized MonicaHQ

Completely Dockerized MonicaHQ (personal CRM).

This is basically https://www.monicahq.com/ in a self contained, simple to run
repo. They provide the docker container, but some other things are needed in
order for it to run, like the DB, so here I provide a way to run it with one
single command.

Here is the original code from where the docker images I'm using come from:

- https://github.com/monicahq/monica


## Requirements:

- `docker-compose`


## How to run:

- Be in the root directory of the project
- `docker-compose up`
- Now you may go to http://localhost


## How to use it:

- You'll need to create an account.
- Click on sign up.
- Put any email address you like, name and password
- You'll see an error, that's because it can't send an e-mail to you from the
containers (need to fix this).
- Go back to login, and insert the email you picked and the password and you
should be taken to your dashboard.


## How to contribute:

I want to keep this repo as simple as possible, the only requirement I have is
that we keep defaults sane and simple.
