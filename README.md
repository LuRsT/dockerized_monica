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

## How to contribute:

I want to keep this repo as simple as possible, the only requirement I have is
that we keep defaults sane and simple.
