# ISEC6000 Assignment 2
Kristian Frossos, Student No. 20853161

## Table of Contents
* [Introduction](#introduction)
* [Cloning](#cloning-this-repository)
* [Requirements](#requirements)
* [Run](#running-the-project)
* [Usage](#usage)

## Introduction
Project containing docker compose file for ISEC6000 Secure Dev Ops - Assignment 2, semester 2 2023 by Kristian Frossos.

## Cloning this repository
To clone this repository to your own machine, enter the following:
```shell
git clone https://github.com/Frosk-Kristian/Project2-Compose.git
```

## Requirements
* Minimum server requirements.
    * Ubuntu 20.04 or later.
        * Tested with WSL2 running Ubuntu 22.04.2 LTS.
    * 1GB of RAM.
    * 2 CPU cores.
    * 10GB free space.
* Docker Engine
* Docker Compose

## Running the Project
### Run the application
In the directory you've cloned this repository to, enter the following:
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
