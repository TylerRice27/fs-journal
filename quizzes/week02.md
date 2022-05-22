# Intro to JavaScript
.
**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A set of statements that performs a task or calculates a value
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation,Dependency Inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple position is number 2. The reason for number 2 and not 3 is because all
arrays first item start from a position of 0 not 1.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
for (let i of them){
  you.push(i)
}
return You

or 
Array.push.apply(you,them)
log(you)

```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
 if statement like 

if(100 > 2){
  return "Good Job"
}

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js"
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. The Head file is first accessed to read the webpage.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
 Primitive Values, Boolean type, Null type, Undefined type, Number type, BigInt type, String type, Symbol type and Objects
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are used when defining a function, they are the names created in the function definition. They also go in the (). Arguments are the value that the function receives.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value type is identified by the variable you for declaration in your program.
Example 
let fruit = orange

A reference value is considered an object and therefore have methods examples of these are arrays and functions.
```