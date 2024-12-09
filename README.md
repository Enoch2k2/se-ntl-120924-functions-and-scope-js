### Functions & Scope

/*
Agenda
----
0. If statements
1. What is a function?
2. console.log vs return
3. arguments
4. default arguments
5. functions within functions
6. callbacks
7. scope

*/

// let name = "Bob";

// now we have this fork in the road

// if the name is Sam, they can go left

// if the name is all lowercase, they can go middle

// otherwise they can go right

// if(name == "Sam") {
//   console.log('Name is Sam')
// }
// else if (name.toLowerCase() === name) {
//   console.log('Name is all lowercase')
// }
// else {
//   console.log("Name is not Sam and not lowercase")
// }
// null, false, NaN, undefined, 0
// if(name) {
//   console.log("This will always run")
// }

// function sum(a, b) {
//   let result = a + b
//   console.log('the result is: ' + result)
// }

// sum(1, 1)
// sum(2, 2)
// sum(2, 3)
// sum(3, 1)
// sum(4, 5)
// sum(10, 10)

// function greeting(name="Javascript Programmer") {
//   console.log(`Hello ${name}!`)
// }

// greeting("Aidan")
// greeting("Adrian")
// greeting()

// function animalWithSuperpower(animal) {
//   return function(superpower) {
//     console.log(`the animal is: ${animal} and it's superpower is ${superpower}!`)
//   }
// }

// let hippoCreator = animalWithSuperpower("Hippo")

// hippoCreator("really strong jaws")
// hippoCreator("really fast swimmer")

// function doMath(num1, num2, callback) {
//   let result = callback(num1, num2)
//   console.log('the result is: ' + result)
// }

// function add(num1, num2) {
//   return num1 + num2
// }

// function subtract(num1, num2) {
//   return num1 - num2
// }

// function multiply(num1, num2) {
//   return num1 * num2
// }

// const divide = (num1, num2) => num1 / num2

// doMath(1, 3, add)
// doMath(3, 1, subtract)
// doMath(3, 3, multiply)
// doMath(3, 3, divide)
// doMath(2, 2, (a, b) => a ** b)

// let name = "Bob" // Global Scope

// function greeting(name) {
//   name = "Sam"

//   console.log(name)
// }

// greeting(name)
// console.log(name)
