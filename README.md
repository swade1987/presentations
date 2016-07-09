# Presentations

This is a repository to store all my reveal.js presentations allowing them to be ran in a Docker container locally.

## Example usage

```bash
$ docker build -t="swade1987/presentation" .
$ docker run -p 8000:8000 --name example-presentation -v $(pwd)/example-presentation:/opt/reveal.js/slide-deck -d "swade1987/presentation"
```

## View the presentation

Browse to http://localhost:8000/slide-deck#/