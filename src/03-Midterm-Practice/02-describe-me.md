# Describe Me - A Lesson on Data Types

![Cute bunch of 4 kittens](./../assets/images/cute-kittens.jpg)

Let's pause for a second and make sure that we understand how data are another way to describe our reality. Different types of data and data structures offer us different ways to carry out this descriptive work.

In small groups of 3-4 people, work through the following sections that ask you to describe the above image of kittens with different types of data primitives and data structures.

<p class="warning">
  Be sure to render your variables to the page in a separate codeblock, so you know the code is working.
</p>

## 1. String

Create a variable that is assigned a String that describes this image in 1-2 sentences.

```js
let description = "A group four kittens with striking blue eyes piled on top of each other. From left to right, there is a gray striped kitten, an orange kitten, another gray striped kitten, and a brown striped kitten."
```

## 2. Array

Create a variable that is assigned to an Array that has 4 or more values to describe this image.

```js
let kittyArray = [
  "Spot",
  "Garfield",
  "Smalls",
  "Squish",
]
```

```js
kittyArray
```

## 3. Object

Create a variable that is assigned 1 object with at least 4 key-value pairs.

```js
let leftKitty = {
  "name": "Spot",
  "position": 1,
  "color": "gray",
  "eyes": "blue",
}
```

```js
leftKitty
```

## 4. Array of Objects

Create a variable that is assigned an Array with 4 objects that represent each kitten. Make sure that each kitten object shares the same keys.

```js
let kittyObjArray = [
  {
    name: "Spot",
    position: 1,
    color: "gray",
    eyes: "blue",
  },
  {
    name: "Garfield",
    position: 2,
    color: "orange",
    eyes: "blue",
  },
  {
    name: "Smalls",
    position: 3,
    color: "gray",
    eyes: "blue"
  },
  {
    name: "Squish",
    position: 4,
    color: "brown",
    eyes: "blue",
  },
]
```
```js
kittyObjArray
```

## Helpful Transformative Methods in JS

We should remember a few useful methods, when working with the above types of data. Let's practice some of them together:

### Strings

```js
/**
 * Strings:
 * concatenation, .charAt(), .slice(), .split()
**/
description+" Adding more words is concatenation!"
```

```js
description.charAt(6) //tells you what "char"acter is at a certain position
```

```js
description.slice(4, 10) //prints positions between these two positions
```

```js
description.split("") //divides by a certain character (like a . can divide by sentences)
```
### Arrays

```js
/**
 * Arrays:
 * Using index position, .push(), for loops, .map()
**/

kittyArray.push("new name") //pushes new data point to the array
```
```js
kittyArray.map(
  //accessor function
  (kitty) => {
    console.log("value:", kitty)
  }
) //returns the data points from the array (you can also "map" new values to them)
```

### Objects

```js
/**
 * Objects:
 * Accessing values with keys; Adding new properties (key-value pairs)
**/

leftKitty.eyes //can also be array["value"] like leftKitty["eyes"]
```

### Array of Objects

```javascript
/**
 * Array of Objects:
 * Looping through and accessing properties with keys;
 * Adding new props;
 * Difference between .map() and for loops
**/

//map can make each value an object instead of just a string
```
