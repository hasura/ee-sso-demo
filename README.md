# Console SSO for Hasura GraphQL Engine Enterprise demo

## Introduction

This is a console SSO integration demo for Hasura GraphQL Engine Enterprise with popular protocols:

- OAuth 2.0/OpenID Connect (Auth0)
- SAML (Dex + Auth0)
- LDAP (Dex + OpenLDAP)

## Get Started

- Copy the environment variables file `dotenv` to `.env`, configure secrets and the [EE License Key](https://hasura.io/docs/latest/enterprise/upgrade-ce-to-ee/).

- Start services with `docker-compose`

```sh
cp dotenv .env
docker-compose up -d
```

## Configuration and Tutorials

See the [Enable Single Sign-on](https://hasura.io/docs/latest/enterprise/sso/index/) page in Hasura Enterprise Docs. 