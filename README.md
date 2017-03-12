# Docker Compose
This is a simple Docker Compose example

## Requirements
Make sure you don't have anything listening locally on port 8081 before continuing.

### Environment
* [Docker](https://docs.docker.com/engine/getstarted/step_one/)
* [Docker Compose](https://docs.docker.com/compose/install/)

## Quick Start
The following command will setup and start the services:

```bash
docker-compose up -d
```
> Roughly takes about 2-10 minutes.

To make sure all the service came up without any issues. Use the following command:

```bash
docker-compose ps
```

Once everything is good, you should be able to open a browser and hit the URL, http://localhost:8081
