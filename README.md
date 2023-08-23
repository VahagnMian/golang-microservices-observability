![Group 1](https://github.com/VahagnMian/golang-microservices-observability/assets/63123814/9e6e4904-ba9f-49ad-8f7f-5dee082854f1)
# Observability for simple Microservices written in Golang

Welcome to our awesome microservices project written in Go!

## 🛠 Pre-requisites

Before diving in, ensure you have the following:

1. **`psql`**: Not installed? 🛑 Installation both for Mac and Ubuntu Follow the guide [here](https://www.timescale.com/blog/how-to-install-psql-on-mac-ubuntu-debian-windows/).

2.  Execute the following commands to set up your database:
```bash
docker-compose up -d postgres
psql -h localhost -p 5432 -U postgres -c "CREATE DATABASE users;"
psql -h localhost -p 5432 -U postgres -d users -a -f ./resources/users.sql
```

### How to run
```bash
docker-compose up --build -d
```

