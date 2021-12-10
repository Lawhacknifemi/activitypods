[![SemApps](https://badgen.net/badge/Powered%20by/SemApps/28CDFB)](https://semapps.org)

# ActivityPods

> ActivityPub + Solid PODS = ❤️

Check out [these slides](./proposal/proposal-english.pdf) ([french version](./proposal/proposal-french.pdf)) for more information about this project !

## Getting started

```
yarn install
yarn run bootstrap
docker-compose up -d fuseki
cd boilerplate
yarn run dev
```

## Available applications

- [Contacts](packages/contacts/README.md)
- [Events](packages/events/README.md)
- [Messages](packages/messages/README.md)

## Deployment

Follow the guide [here](deploy/README.md).

## Tests

```
yarn install
yarn run bootstrap
docker-compose up -d fuseki_test
cd tests
yarn run test
```
