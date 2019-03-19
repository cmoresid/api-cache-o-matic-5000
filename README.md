# api-cache-o-matic-5000

This is a caching layer around an unreliable API.

## Pre-requistes

- docker-compose
- Node.js ~8.15.Xs

## How to run

1. `npm install`
2. `docker-compose up`
3. `npm run watch`

## Contributing

This project currently uses git hooks to validate commit messages in order to ensure consistency. To run the commit helper, run:

`npm run commit`

Also - there is a pre-commit hook that will automatically prettify any \*.ts files.
