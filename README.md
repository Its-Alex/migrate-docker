# Migrate Docker

Create image for current [migrate](https://github.com/golang-migrate/migrate)

## How to use

For up migration

```
$ docker run -v {{ migration dir }}:/migrations itsalex/migrate -paht=/migrations/ -database {{ database schema }} up
```
