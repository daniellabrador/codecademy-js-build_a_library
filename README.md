# **Build a Library**

The Build a Library program is a simple program that allows libraries to create objects for their media using classes. This training project, prepared by [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript), has been an invaluable exercise in creating classes using JavaScript.

## Table of Contents

- [Project Prompt](#project-prompt)
- [Technologies](#technologies)
- [Setup](#setup)
- [Sources](#sources)

## Project Prompt

Congratulations, you’ve become head librarian at your local Books-‘N-Stuff, which is in dire need of your help. They’re still using index cards to organize their content! Yikes.

But no matter, you know some JavaScript, so let’s get to work modernizing your new digs.

Books-‘N-Stuff carries three different types of media: books, CDs, and movies. In this project you will create a parent class named Media with three subclasses: `Book`, `Movie`, and `CD`. These three subclasses have the following properties and methods:

### Book

- Properties: `author` (string), `title` (string), `pages` (number), `isCheckedOut` (boolean, initially `false`), and `ratings` (array, initially empty).
- Getters: all properties have a getter
- Methods: `.getAverageRating()`, `.toggleCheckOutStatus()`, and `.addRating()`

### Movie

- Properties: `director` (string), `title` (string), runTime (number), `isCheckedOut` (boolean, initially `false`), and `ratings` (array, initially empty)
- Getters: all properties have a getter
- Methods: `.getAverageRating()`, `.toggleCheckOutStatus()`, and `.addRating()`

### CD

- Properties: `artist` (string), `title` (string), `isCheckedOut` (boolean, initially `false`), and `ratings` (array, initially empty), `songs` (array of strings)
- Getters: all properties have a getter
- Methods: `.getAverageRating()`, `.toggleCheckOutStatus()`, and `.addRating()`

## Technologies

- JavaScript (ES6)

## Setup

To run this program, you needinstall [Node.js](https://nodejs.org/en/download/) to your machine.

Enter this command to the terminal:

```git
node script.js
```

You can freely add and access objects and its properties and methods, or modify current objects created directly in the `script.js` file.

## Sources

The techniques utilized was based on the lessons taught in [Codecademy's Learn JavaScript Course](https://www.codecademy.com/learn/introduction-to-javascript). The challenge is also provided by Codecademy.
