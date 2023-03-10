# Destructuring-inside-variables
const person = {
 name: 'John Doe',
 age: 45,
 location: 'Paris, France',
};
GoalKicker.com – JavaScript™ Notes for Professionals 336
let { name, age, location } = person;
console.log('I am ' + name + ', aged ' + age + ' and living in ' + location + '.');
// -> "I am John Doe aged 45 and living in Paris, France."
