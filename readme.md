# Restaurant app

Project based on PHP Backend Developer technical test for Alegra Company.

This project consists of three web services `order`, `kitchen` & `inventory` and 
one API gateway `api-gateway`.

The webservices are containerised with Docker using php:8.1-apache environment
and Laravel as backend to expose and consume the APIs.

The `api` is using the Guzzle API Client in order to maintain connection with the web services.