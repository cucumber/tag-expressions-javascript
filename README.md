# Cucumber Tag Expressions for JavaScript

[![Greenkeeper badge](https://badges.greenkeeper.io/cucumber/tag-expressions-javascript.svg)](https://greenkeeper.io/)


[The docs are here](https://cucumber.io/docs/cucumber/api/#tag-expressions).

## Example

```js
const tagExpressions = require("@cucumber/tag-expressions")

const expressionNode = tagExpressions.default('@tagA and @tagB')

expressionNode.evaluate(["@tagA", "@tagB"])
expressionNode.evaluate(["@tagA", "@tagC"])
```
