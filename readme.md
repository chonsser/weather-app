# Weather aggregator
This is a small application which shows the average tempature for provided location.

---

## Project setup

This application runs on **Symfony 5** & requires PHP 7.4 installed on your host machine.

As local web server please use the `symfony` CLI tool as local dev-server (`symfony serve`).

For development purposes use the Docker environment. 

Please notice – by default `docker-compose` uses the `.env` file. The variables should fit for development purposes.

**Never use these values & setup in production environment!**

Single-line development setup:
```
docker-compose up -d && symfony serve -d && yarn watch
```
