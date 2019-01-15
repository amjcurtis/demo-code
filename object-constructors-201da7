'use strict';

var tanner = {
  course: '201d44',
  enrolled: true,
  instructor: 'Sam',
  first: 'Tanner',
  lastName: 'Percival',
  preferredName: 'Tan-Man',
  homeTown: 'Tacoma',
  introduction: function () {
    return 'Hi, my name is ' + this.firstName + ' ' + this.lastName + ', but you can call me ' + this.preferredName + '. I am from ' + this.homeTown + '.';
  }
};

// Constructor function syntax

// function ConstructorFunctionName (parameter1, parameter2) {
//   this.property = parameter1;
//   this.property2 = parameter2;
//   this.staticProperty1 = 'ExampleString';
//   this.method1 = function () {
//     console.log('do stuff');
//   };
// }

//====================
// Student Constructor (i.e. for constructing a "Student" object)
//====================

var allStudents = []; // Create array containing all students (pushed from array method at end of function definition)
// ^ Access prprties in objs in allStudents array using this notation: "allStudents[1].firstName"
// console.table(allStudents) // This isn't a valid way to create an HTML table on a page; it's just a way to inspect an object array

function Student(firstName, lastName, preferredName, homeTown) {
    this.course = '201d44';
    this.enrolled = true;
    this.instructor = 'Sam';
    this.first = firstName;
    this.lastName = lastName;
    this.preferredName = preferredName;
    this.homeTown = homeTown;
    allStudents.push(this); // Added this line so we can push each constructed instance to our allStudents array
}

Student.prototype.introduction = function () { // Prototype is big brother to "this." in a way
    return 'Hi, my name is ' + this.firstName + ' ' + this.lastName + ', but you can call me ' + this.preferredName + '. I am from ' + this.homeTown + '.';
}; // Semicolon here b/c this isn't a function *declaration* but rather a function *assgnmnt*

// Creates an "instance" of the Student constructor
var ConstructedTanner = new Student();
//==========================
//Student Prototype Property
//==========================

// new Student instances
