# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram that is used to perform a task
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility Principle
Open Closed Principle
Liskov substitution Principle
Interface Segregation Principle
Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
[2] - because arrays start at an index position of [0]

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(...them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(10 > 5){
  return true
} else {
  return false
};
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
Increment. i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Data Object Model. The HTML file is loaded first. 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
1. Primitive Values
2. Boolean type
3. Null
4. Undefined type
5. Number type
6. BigInt type
7. String type
8. Symbol type
9. Objects
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are the values used to define the function and the argument is the values that get passed when the function is invoked. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values show the actual value that gets presented. When creating a variable with a reference value, the variable isn't assigned to the exact value, only the location of the value.
```