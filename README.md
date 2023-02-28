
# TypeScript Exercises

![App Screenshot](https://i.imgur.com/VZeGBDI.png)

## Exercises

This repository contains a collection of TypeScript exercises designed to test my knowledge of the language. The exercises cover a wide range of topics, from basic syntax and data types to advanced concepts such as object-oriented programming and asynchronous programming.

## Getting Started

To get started with these exercises, you'll need to have TypeScript installed on your machine. If you don't already have TypeScript installed, you can download it from the [TypeScript website](https://www.typescriptlang.org/download).

Once you have TypeScript installed, you can clone this repository to your local machine using the following command:

bashCopy code
- Clone the project

```bash
`git clone https://github.com/rcmtcristian/typescript-exercises.git`
```

- Go to the project directory

```bash
  cd my-project
```

- Install dependencies

```bash
  npm install
```

- Start the server

```bash
  npm run start
```

Alternatively, you can download the repository as a zip file and extract it to your local machine.

## Structure

The repository is structured into folders based on the topic of each exercise. Each folder contains an `index.ts` file with instructions for the exercise and a TypeScript file with some starter code that you'll need to modify to complete the exercise.

To complete an exercise, you'll need to modify the TypeScript file according to the instructions in the `README.md` file. Once you've completed the exercise, you can test your solution by running the TypeScript file using the following command:

Copy code

`tsc filename.ts && node filename.js`

Replace `filename` with the name of the TypeScript file you want to test.

## Content
The folders contain exercise such as the following for example:  

### Exercise Type 1: Variables and Basic Types
Create a TypeScript file named exercise1.ts. In this file, declare a variable for each of the following:

A number
A string
A boolean
An array of numbers
An array of strings
Assign a value to each variable, then log the value of each variable to the console.

### Exercise Type 2: Functions
Create a TypeScript file named exercise2.ts. In this file, create a function that takes two parameters:

A number
A string
The function should return a string that concatenates the number and the string parameter. For example, if the function is called with 3 and "red", it should return "3red".

Call the function with some values and log the result to the console.

### Exercise Type 3: Classes and Interfaces
Create a TypeScript file named exercise3.ts. In this file, define a class called Person. The Person class should have the following properties:

name (string)
age (number)
The Person class should also have a method called greet that logs a greeting to the console. The greeting should include the person's name and age.

Create an interface called IPerson that defines the same properties as the Person class. Implement the IPerson interface on the Person class.

Create an instance of the Person class, set the name and age properties, and call the greet method.

### Exercise Type 4: Asynchronous Programming
Create a TypeScript file named exercise4.ts. In this file, create a function that takes a callback as a parameter. The callback should be called after a random amount of time between 0 and 5 seconds, and should return a random number between 0 and 10.

Call the function and log the result to the console. The result should be a random number between 0 and 10, but the function may take some time to complete. Use async/await to handle the asynchronous behavior.

## Contributing

If you find any issues with the exercises or have suggestions for new exercises, feel free to open an issue or submit a pull request.


## License

[MIT](https://choosealicense.com/licenses/mit/)

