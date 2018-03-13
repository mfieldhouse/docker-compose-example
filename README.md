# Docker Compose Example App

Simple application to demonstrate running a webapp using Docker Compose 
[as demonstrated by Jake Wright](https://www.youtube.com/watch?v=Qw9zlE3t8Ko).

  - `git clone` this repository
  - Run `which docker-compose` to ensure you have docker-compose installed
  - `cd` to the root of the app where `docker-compose.yml` is located
  - Run `docker-compose` up

Two containers will run. The first is the website written in HTML and PHP. It
connects to the second container written in Python to get the list
of products which are returned as JSON.
