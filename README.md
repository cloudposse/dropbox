# Dropbox Service

Implements headless `Dropbox/`

## Caveats

Will not work under `docker-machine` with bind-mounted volumes. Doing so will trigger the error: `OperationalError: disk I/O error`
