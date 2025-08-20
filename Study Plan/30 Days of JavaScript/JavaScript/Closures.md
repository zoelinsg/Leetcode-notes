# LeetCode 30 Days of JavaScript — Closures (JavaScript)

### [2667. Create Hello World Function](https://leetcode.com/problems/create-hello-world-function/description/?envType=study-plan-v2&envId=30-days-of-javascript)

```javascript
var createHelloWorld = function() {
    return function(...args) {
        return "Hello World";
    }
};
```