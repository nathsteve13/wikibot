# wikibot
This project is about making a wikibot with adopted fully continous integrated &amp; development architecture using python

[![Python application test with Github Actions](https://github.com/nathsteve13/wikibot/actions/workflows/main.yml/badge.svg)](https://github.com/nathsteve13/wikibot/actions/workflows/main.yml)
[![Python application test with Github Actions](https://github.com/nathsteve13/wikibot/actions/workflows/main.yml/badge.svg)](https://github.com/nathsteve13/wikibot/actions/workflows/main.yml)


### To call microservice 

```bash
curl -X 'POST' \
  'https://noahgift-functions-from-zero-r7g59wcxx6x-8080.githubpreview.dev/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'
```

### Build container

`docker build.`
`docker image ls`

### Run container

`docker run -p 127.0.0.1:8080:8080 wikibot`

## Invoke POST request

run `invoke.sh`