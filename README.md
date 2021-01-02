# saml-multi-tenancy

> We are using custom datastore `mongodb` and own authentication method using jwt in `nodejs`.

Install the server dependencies

```sh
git subtree push --prefix server heroku master
```
https://saml-multitenancy.herokuapp.com/

```
heroku config:set "MONGODB_URI=mongodb_srv://<username>:<password>@cluster0-..."
heroku config:set "SALT=8"
heroku config:set "JWT_SECRET=supersecret"
```