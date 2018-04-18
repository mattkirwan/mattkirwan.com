# My Personal Website

## Development

`docker-compose up -d nginx`

Site available at https://mattkirwan.test

Make changes in `/public`

## Build

`docker build -f dockerfiles/build -t lksoia89/site:0.0.1 .`
`docker push lksoia89/site:0.0.1`

## Test

`docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d site`

## Release

Upgrade service in Rancher.
