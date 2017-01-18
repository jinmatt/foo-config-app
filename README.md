# Configuration Management demo app(Node.js/Express.js)

How to run:

```
$ git clone git@github.com:jinmatt/foo-config-app.git
$ cd foo-config-app

# Install dependencies, you can use yarn or npm
$ yarn

# Start with staging config in debug mode:
$ NODE_ENV=staging DEBUG=foo-config-app:server npm start

# Or run in production config:
$ NODE_ENV=production npm start
```

If `NODE_ENV` is not set `default.json` config is loaded by the config manager, which can be used in development environments as the default config.
