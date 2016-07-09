# Presentations

A repository for all my reveal.js presentations.

## Installation

Install Docker for Mac from here - https://docs.docker.com/docker-for-mac/
Install Docker for Windows from here - https://docs.docker.com/docker-for-windows/

## Setup

Edit your host file and add the following line

| O.S           | Location                                  |
| ------------- |:-----------------------------------------:|
| OSX           | /etc/host                                 |
| Windows       | C:\Windows\System32\drivers\etc\hosts     |

```bash
$ *.docker.localhost localhost
```

Execute the following commands:

```bash
$ docker build -t="swade1987/presentation" .
$ docker-compose up -d
```

Now browse to http://docker101.docker.localhost/slide-deck