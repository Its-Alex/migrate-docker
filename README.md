# Migrate Docker

Create image for current [migrate](https://github.com/golang-migrate/migrate)

## How to use

For up migration

```
$ docker run -v {{ migration dir }}:/migrations --network host itsalex/migrate-docker 
    -path=/migrations/ -database {{ database schema }} up
```

# DEPRECATED

Now [migrate](https://github.com/golang-migrate/migrate) has it's own docker image
