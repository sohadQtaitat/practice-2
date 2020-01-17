# practice-2
301 Practice Assignment 2

practice-2
Q1- In a Handlebars template, what does {{city}} refer to?


 A handlebars expression is a {{, some contents, followed by a }}. When the template is executed, these expressions are replaced with values from an input object.



Q2- Explain how the following code in a Node-express server is triggered to run, and what it's output is ?

server.get('/list', (request, response) => { let animals = ['Cat','Dog','Sheep']; response.send(200).json(animals); });

when type the rout(/list) and print out the array of animals since the status is "200" has succeeded then show the arr animals
 




Q3- Write a Constructor function that can create an instance of a person, with a name and an age, given 2 arguments



function Person (name,age) { this.name = name; this.age = age; }

let person = new Person ('sohad',31); console.log(person);


