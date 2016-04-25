# Islandora CLAW: Open JDK Docker Image

[![Docker Stars](https://img.shields.io/docker/stars/islandora/claw-open-jdk.svg)](https://hub.docker.com/r/islandora/claw-open-jdk/)
[![Docker Pulls](https://img.shields.io/docker/pulls/islandora/claw-open-jdk.svg)](https://hub.docker.com/r/islandora/claw-open-jdk/)

## Introduction

Defines the Java Docker image from which we build our Java based images (Tomcat, Karaf, etc), uses OpenJDK.

Based on the [Base Docker Image](https://github.com/Islandora-CLAW/docker-base).

## Includes

* OpenJDK 8

## Build Arguments

No build arguments are provided.

**Example:**
```bash
docker build -t islandora/claw-open-jdk .
```

## Environment Variables

| Variable  | Required | Default |
|-----------|----------|---------|
| JAVA_OPTS | no       |         |

**Example (foreground, auto-remove, interactive shell):**
```bash
docker run --rm -ti islandora/claw-open-jdk ash
```

## Commands

For convenience a number of commands are provided in the [commands](/commands) folder.

| Command | Arguments | Defaults | Notes                                                                 |
|---------|-----------|----------|-----------------------------------------------------------------------|
| build   |           |          | Build this image with the default settings.                           |
| run     |           | ash      | Start container, execute the given arguments as a command, then exit. |

## Maintainers/Sponsors

* UPEI
* discoverygarden inc.
* LYRASIS
* McMaster University
* University of Limerick
* York University
* University of Manitoba
* Simon Fraser University
* PALS
* American Philosophical Society
* common media inc.

Current maintainers:

* [Nigel Banks](https://github.com/nigelgbanks)
* [Nick Ruest](https://github.com/ruebot)

## Development

If you would like to contribute, please get involved by attending our weekly [Tech Call](https://github.com/Islandora-CLAW/CLAW/wiki). We love to hear from you!

If you would like to contribute code to the project, you need to be covered by an Islandora Foundation [Contributor License Agreement](http://islandora.ca/sites/default/files/islandora_cla.pdf) or [Corporate Contributor Licencse Agreement](http://islandora.ca/sites/default/files/islandora_ccla.pdf). Please see the [Contributors](http://islandora.ca/resources/contributors) pages on Islandora.ca for more information.

## License

[MIT](https://opensource.org/licenses/MIT)
