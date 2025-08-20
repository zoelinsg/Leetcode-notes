# LeetCode 30 Days of JavaScript — Closures (TypeScript)

### [2667. Create Hello World Function](https://leetcode.com/problems/create-hello-world-function/description/?envType=study-plan-v2&envId=30-days-of-javascript)

```typescript
const createHelloWorld = (): (...args: any[]) => string => {
    return function (...args: any[]): string {
        return "Hello World";
    };
};
```