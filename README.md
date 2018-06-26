## Creating new project

With Serverless Framework v1.5 and later, a new project based on the project template is initialized with the command

```
> sls install -u https://github.com/nordcloud/serverless-boilerplate -n myservicename
> cd myservicename
> npm install
```

## Testing vulnerabilities

Test vulnerabilities with NSP using
```
> npm run nsp
```

## Comparing setup with boilerplate

You can compare your project setup (dependencies, devdependencies, scripts) with the boilerplate using the command

```
> npm run compare-boilerplate
```

The script reports only for items that are in the boilerplate and differ from your current project.

// "coverage": "nyc report --reporter=text-lcov | coveralls",
// "deploy:init": "serverless create_domain",
// "postdeploy": "npm run test:integration",
// "test": "nyc mocha",
// "test:integration": "mocha --opts ./test/integration/mocha.opts",