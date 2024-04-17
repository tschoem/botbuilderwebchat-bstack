# Run Botium-based chat tests using Botium Connector for WebdriverIO with Browserstack

This project provides a working example of web-based chat bot tests based on the botium sample "botbuilder-webchat".

## Requirements

- Node.js and NPM
- A Browserstack account (User name and access key) for running tests on **Browserstack**
- A Running selenium grid for tests to run locally / somewhere else

## Step 1 - dependencies

Install all dependencies

```
> npm install
```

## Step 2 - configure access to Browserstack

Edit _botium-browserstack.json_ and replace BROWSERSTACK*USERNAME and BROWSERSTACK_ACCESS_KEY with your credentials
You may also edit \_botium.json* to make sure your local selenium grid is properly configured (hostname, port and protocol values)

## Step 3 - run your tests

To run your tests locally

```
> npm test
```

To run your on **Browserstack**

```
> npm run test-bstack
```
