# Firebase Emulator Docker

The repo contains a starting point for starting your own Firebase Emulator Docker instance.

## Quickstart

```
docker compose up --build
```

## Configuration

### Firebase Version

You can change the version of Firebase you want to use in `emulator/Dockerfile` and `compose.yml`

### Firebase Configuration

You can change your Firebase configuration in `firebase/firebase.json`

## Default Page Preview Links

You can access the emulator dashboard at `http://localhost:4000`

## References

1. [Docker: A Guide to Local Development and Testing](https://medium.com/@jens.skott_65388/simplifying-firebase-emulation-with-docker-a-guide-to-local-development-and-testing-0c3c33fd92c7)
2. [docker-firebase-emulator](https://github.com/thoughtgears/docker-firebase-emulator)
