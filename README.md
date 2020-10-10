# crypto-timestamp-api

## Usage

There's several ways to launch it:

1. Dev: API and migrations on your local machine, postgres in Docker (+ adminer in Docker for convenience):
   Run it with:

```
make
```

2. Full-docker: API, migrations, postgres and adminer each in a Docker container:
   This mode is intended for deployment. Run it with:

```
# TODO
```

## Configuration options

Configure with:

- Environment variables (ony for config options, not for secrets)
- Config files (provided via docker volume): both for config options and for secrets
