# sentry-demos/vue-js

## Project setup
1. Use the nvmrc file to set a compatible node version.
```
nvm use
```

2. Install dependencies
```
npm install
```

3. Create a VUEJS Sentry project and configure Sentry with your `PUBLIC_DSN_KEY` in App.vue
4. Remember to include your `SENTRY_AUTH_TOKEN`; you'll need to generate one
first from your Sentry server. After doing so, a cheap and easy way to use the
token would be this: `export SENTRY_AUTH_TOKEN=1010101011010101`
5. Enter your Sentry organization slug in the `SENTRY_ORG` line of your Makefile,
then add the name of `SENTRY_PROJECT`
6. Make sure that your Github repo is integrated into your Sentry organization.

```
$ npm run deploy
```

![Alt Text](configure-launch-vuejs-demo.gif)