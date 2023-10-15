# ISEC6000 Assignment 2
Kristian Frossos, Student No. 20853161

## Table of Contents
* [Introduction](#introduction)
* [Requirements](#requirements)
* [Run](#running-the-project)
* [Usage](#usage)

## Introduction
Project containing docker compose file for ISEC6000 Secure Dev Ops - Assignment 2, semester 2 2023 by Kristian Frossos.

## Requirements
* Minimum server requirements.
    * Ubuntu 20.04 or later.
        * Tested on Windows 10 with WSL2 running Ubuntu 22.04.2 LTS.
    * 1GB of RAM.
    * 2 CPU cores.
    * 10GB free space.
* Docker Engine
* Docker Compose

## Runnning the Project
### Run the application
```shell
docker compose up -d
```
The flag `-d` runs containers in the background, printing container id.

### Stop the application
```shell
docker compose stop
```

### Remove volumes
```shell
docker compose rm
```

### Prune cache
```shell
docker system prune
```

## Usage
After running the application as [previously outlined](#run-the-application), you can access its' components at the following ports on the host machine:
* dind:
    * 2376
* jenkins:
    * 8080
    * 50000

*[Back to top](#isec6000-assignment-2)*
