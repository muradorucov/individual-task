# Javascript Object Tasks

## Task-01: Create a function that takes an object and returns an array of its keys.
```javascript
function getObjectKeys(obj) {
    return Object.keys(obj);
}
```
## Task-02: Create a function that takes an object and returns an array of its values.
```javascript
function getObjectValues(obj) {
    return Object.values(obj);
}
```
## Task-03: Create a function that takes an object and returns an array of its entries (key-value pairs).
```javascript
function getObjectEntries(obj) {
    return Object.entries(obj);
}
```
## Task-04: Create a function that takes an object and a key, and returns the value associated with that key.
```javascript
function getValueByKey(obj, key) {
    return obj[key];
}
```
## Task-05: Create a function that takes an object and a key, and returns true if the key exists in the object, false otherwise.
```javascript
function hasKey(obj, key) {
    return obj.hasOwnProperty(key);
}
```
## Task-06: Create a function that takes an object and a key, and deletes the key-value pair from the object.
```javascript
function deleteKey(obj, key) {
    delete obj[key];
}
```
## Task-07: Create a function that takes an object and a key, and adds a new key-value pair to the object.
```javascript
function addKeyValuePair(obj, key, value) {
    obj[key] = value;
}
```
## Task-08: Create a function that takes an object and returns a new object with only the keys that exist in the original object.
```javascript
function filterObjectKeys(obj, keys) {
    return Object.fromEntries(Object.entries(obj).filter(([key]) => keys.includes(key)));
}
```
## Task-09: Create a function that takes an object and returns a new object with only the values that are strings.
```javascript
function filterObjectValues(obj) {
    return Object.fromEntries(Object.entries(obj).filter(([key, value]) => typeof value === 'string'));
}
```
## Task-10: Create a function that takes an object and returns a new object with only the values that are numbers.
```javascript
function filterObjectNumbers(obj) {
    return Object.fromEntries(Object.entries(obj).filter(([key, value]) => typeof value === 'number'));
}
```
## Task-11: Create a function that takes an object and returns a new object with only the values that are arrays.
```javascript
function filterObjectArrays(obj) {
    return Object.fromEntries(Object.entries(obj).filter(([key, value]) => Array.isArray(value)));
}
```
## Task-12: Create a function that takes an object and returns a new object with only the values that are objects.
```javascript
function filterObjectObjects(obj) {
    return Object.fromEntries(Object.entries(obj).filter(([key, value]) => typeof value === 'object' && !Array.isArray(value)));
}
```
## Task-13: Create a function that takes an object and returns a new object with only the values that are booleans.
```javascript   
function filterObjectBooleans(obj) {
    return Object.fromEntries(Object.entries(obj).filter(([key, value]) => typeof value === 'boolean'));
}
```
