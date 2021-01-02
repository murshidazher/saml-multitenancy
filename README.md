# saml-multi-tenancy

> We are using custom datastore `mongodb` and own authentication method using jwt in `nodejs`.

- OneLogin
- [Configure OneLogin as SAML Identity Provider](https://auth0.com/docs/protocols/saml-configuration-options/configure-onelogin-as-saml-identity-provider) and [setup](http://communicocollege.com/onelogin-setup-1262)

Install the server dependencies

## Development

> Heroku hosted [URL](https://saml-multitenancy.herokuapp.com/)

```sh
git subtree push --prefix server heroku master
```

Heroku `env` variable list

```
heroku config:set "MONGODB_URI=mongodb_srv://<username>:<password>@cluster0-..."
heroku config:set "SALT=8"
heroku config:set "JWT_SECRET=supersecret"
```

## License

[MIT](https://github.com/murshidazher/saml-multtenancy/blob/master/LICENSE) © Murshid Azher.