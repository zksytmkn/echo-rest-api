# echo-rest-api
```
# create module
go mod init go-rest-api
# start db
docker compose up -d
# remove db
docker compose rm -s -f -v
# start app
GO_ENV=dev go run .
# run migrate
GO_ENV=dev go run migrate/migrate.go
```
# Architecture of REST API (Go/Echo) application
![architecture](https://github.com/zksytmkn/echo-rest-api/assets/86869822/c36e64da-fac4-4c01-94fa-9f9a111ab465)
