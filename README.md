
# Virtual Keyboard

A side project I completed whilst studying on School of Code.

The keyboard is created entirely in vanilla JavaScript and uses no external libraries.

My biggest takeaway from completing this project is the flexibility of JavaScript. It feels like we have verged very close to working in an OOP(Object Oriented Programming) paradigm.

## Learning from completing this project
- Importing a custom font family (Material Icons from Google in this case)
- Introducing myself to BEM (Block Element Modifier) naming conventions in CSS
- Using basic Flex in CSS
- Using vanilla JavaScript to:
    - Create HTML elements
    - Append HTML elements to the DOM (Document Object Model)
    - Select HTML elements from the DOM using query selector
    - Toggle CSS classes
    - Using pseudo selectors in CSS
    - Add event listeners
    - Create and trigger "custom" events (e.g. close keyboard)

## Challenges faced
- Understanding the keyboard being a huge object and navigating it using "this." syntax
- Debugging
    - 2 bugs remained after my initial attempt at the keyboard:
        - The caps lock light was not toggling to change the CSS
        - The done key was not closing the keyboard
