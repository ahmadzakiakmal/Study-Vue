# Reactivity Summary

## Vue 2

Primarily utilizes **function** and `Object` to manipulate the data as well as the DOM for reactivity.

## Vue 3

Utilizes `Reflect` and `Proxy` to update values and DOM for reactivity.

### Reflect

Reflect provides static methods to perform low-level operations on objects, such as `get()`, `set()`, `has()`, and `deleteProperty()`. These methods returns `boolean` to indicate whether or not the operation was successful.

### Proxy

Is an object that intercepts object operation. This allows us to provide additional operations when an object is being manipulated (mostly the **Reflect** Operations) to process them further. **In this reactivity concept, it is mostly used to update the DOM when data values are being changed**.