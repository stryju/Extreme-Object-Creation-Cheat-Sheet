# Extreme-Object-Creation-Cheat-Sheet
Extreme Object Creation Cheat Sheet

## Basic

```js
const o1 = {}
const o2 = new Object();
const o3 = Object.create(null);
```

## Extended

```
const o4 = Object();
const o5 = new (function(){});
const o6 = JSON.parse('{}');
```

## Extreme

```
const o7 = null;
const o8 = new Object.prototype.constructor;
const o9 = new Object(Object.prototype);
```
