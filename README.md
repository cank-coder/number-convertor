# Introduction
Hello!

This program is designed to convert number into words.

# Assumptions
There are a number of assumptions made below for the number convetor. 

1. Number Input is invalid if any character is attached to it. For example #23434, $94

2. Multiple separate numbers in a one line input is treated as invalid eg. 23 34

3. This program runs up to a billion numbers provided as input

# Usage

1. Install node and run `npm install`. 
2. npm i number-to-words-convertor
3. Try it: 
    ```
        var convertors = require('number-to-words-convertor');

        console.log(convertors.convertNumberToWords("1243"));

    ```

# Running test

1. Install nodejs (Only required if node not already installed) and run `npm install`. 
2. Run `npm test`