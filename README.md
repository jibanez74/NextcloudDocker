# Nextcloud with Docker
# NextcloudDocker
Simple dockercompose configuration for running nextcloud
# Run it
Add a .env file at the same level as the docker-compose file, add all the necesary variables inside of it and then run:

```sh
docker compose up -d
```

You can then open your browser in http://localhost:8080 and follow the on screen instructions.

# NOTE
This docker configuration is only ment to be run in a local environment.

If you need access from outside your network, I would suggest using https or using something like wireguard to communicate between your nodes.