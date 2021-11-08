# serverless-tag-api-gateway

Serverless plugin to tag API Gateway globally

Instead of tagging desired API Gateway API's stage as it does in <a href="https://www.npmjs.com/package/serverless-tag-api-gateway"> original package</a>, it attaches tag to API only

## Installation

Install the plugin via <a href="https://docs.npmjs.com/cli/install">NPM</a>

```
npm install --save-dev serverless-tag-api-gateway-global
```

## Usage

In Serverless template:

```
custom:
  apiGatewayTags:
    TagName1: TagValue1
    TagName2: TagValue2

plugins:
  - serverless-tag-api-gateway-global

```
