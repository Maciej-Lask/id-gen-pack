# Random Identifier Generator Script (randomID)

The `index.js` script is a simple Node.js module that generates a random identifier of a specified length. Below is a brief description of how the script works and how to use it.

## Installation

To use this script, you need to have Node.js installed on your computer. If you haven't installed it yet, you can download it from the [official website](https://nodejs.org/).

Use yarn command to access the package

yarn add @macielask/randomid-generator

## Usage

Below is an example of how to use the script in your code:

```javascript
const randomID = require('@macielask/randomid-generator');

const idLength = 10; // Specify the desired length of the identifier
const id = randomID(idLength);
console.log(`Generated random identifier: ${id}`);

The randomID Function

The randomID function takes a single argument idLength, which specifies the length of the generated identifier. The function generates the identifier by randomly selecting characters from a set of letters (both uppercase and lowercase) and digits.

License

This project is licensed under the MIT License.

Thank you for using this script!