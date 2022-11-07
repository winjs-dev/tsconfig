# @winner-fed/tsconfig

TSConfigs for projects to extend. Based on [@vue/tsconfig](https://github.com/vuejs/tsconfig).

Requires TypeScript >= 4.5.

Install:

```
npm add -D @winner-fed/tsconfig
```

Add one of the available configurations to your tsconfig.json:

The base configuration (runtime-agnostic):

```
"extends": "@vue/tsconfig/tsconfig.json"
```

Configuration for Browser environment:

```
"extends": "@vue/tsconfig/tsconfig.web.json"
```

Configuration for Node environment:

```
"extends": "@vue/tsconfig/tsconfig.node.json"
```
