# compose.yaml Files

A collection of ready to use Docker compose files.
Fully opiniated for personal self-hosting purpose.

## Guides

- [Running Microsoft SQL Server with Docker Compose](https://www.junian.dev/blog/sql-server-docker-compose/)

## Setup

Most of the compose files here can be connected to each other using a custom network called `devnet`.

You need to create this network first be executing this command.

```bash
docker network create devnet
```

Most of this compose will just work out of the box.
But some requires to set environment variable.

## License

MIT, duh.
