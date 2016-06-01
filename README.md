# Presentations

This is a repository to store all my reveal.js presentations allowing them to be ran in a Docker container locally.

## Example usage

```bash
$ docker-machine create --driver virtualbox default
$ docker build -t="swade1987/docker-revealjs" .
$ docker run -p 8000:8000 --name "docker-revealjs" -v $(pwd)/example-presentation:/opt/reveal.js/slide-deck -d "swade1987/docker-revealjs"
```

## View the presentation

View the on-line presentation:

- http://127.0.0.1:8000/slide-deck#/
- http://BOOT2DOCKER-IP:8000/slide-deck, OS X users should replace `BOOT2DOCKER-IP` with `$(boot2docker ip)`

## Export as PDF

Point web browser to:

- http://127.0.0.1:8000/slide-deck/?print-pdf

Print, and select "save as PDF".