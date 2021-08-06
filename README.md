# vue-cli-service-es-lint-node_modules on an Ionic Vue app

## Mininum system requirement
- node v15.11.0
- npm 7.6.0

## Steps to reproduce the issue
```
npm install
ionic capacitor build ios --verbose
```

The `node_modules` linting error happens on this command as well:
```
./node_modules/.bin/vue-cli-service --skip-plugins @vue/cli-plugin-eslint build
```
