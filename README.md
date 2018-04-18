# My Personal Website

## Development

`docker-compose up -d site`

Site available at https://mattkirwan.test

Make changes in `/public`

## Build

`docker build -f dockerfiles/build -t lksoia89/site:SEMVER .`
`docker push lksoia89/site:SEMVER`

## Release

Upgrade service in Rancher.
