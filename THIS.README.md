# About this Repo

## Bash Scripts

### `start-client.sh`

This script packages and starts the `demo-client` application. The launch config in `launch.json` could also be used.

### `start-quoters.sh`

This script packages and starts the `spring-quoters-api` application. The launch config in `launch.json` could also be used.

## Glowroot

To install Glowroot simply execute `unzip ./glowroot-0.14.5-beta.2-dist.zip`. There is a launch config in the `launch.json` that already has the agent set up, but you'll want to switch the `demo.mode` in `demo-client/src/main/resources/application.properties` to only have the `demo.mode=glowroot` option uncommented and the other 3 commented out.
