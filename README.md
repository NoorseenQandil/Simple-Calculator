# Simple-Calculator
Simple Calulator with HTML, CSS, and java script

## Calculator Design
![Calculator Image](https://github.com/NoorseenQandil/Simple-Calculator/assets/70522199/67c8d95c-1918-4e80-8599-f52939fb8048)

## Features
### 1.User-Friendly Interface:
* The user interface is clean, intuitive, and easy to navigate.
* A visually appealing layout ensures a positive user experience.

### 2.Numbers Buttons
* There are nine buttons for the nine numbers from 1 to 9.
* There is a button for 0.
* There is a button for 00.

### 3.Reset Button
* AC button. It is a reset button, deletes all the entered numbers.

### 4.Delete Button
* DE button. It is a button to delete the last entered number.

### 5.Operator Buttons
* = operator to calculate the result.
* Sumition operator : + 
* Subtract operator : -
* Multiplication operator : *
* Divsion operator : /

## Getting Started
1- Clone or download this repository to your local machine.

2- Open the index.html file in a web browser.

## Java script Functions
- To press on the number and the number is shown on the screen
```
 onclick="display.value +='7'"
```
as 'display' is name value od the screen input

- AC is a reset button, deletes the shown numbers
```
 onclick="display.value =' '"
```

- DE is a button to delete the last entered number
```
 onclick="display.value = display.value.toString().slice(0, -1)"
```

- To calculate the result:
```
 onclick="display.value = eval(display.value)
```
## Live Demo
Experience the Tabs Project in action! Click the link below to access the live demo:

[Live Demo] ([https://your-live-demo-url](https://noorseenqandil.github.io/Simple-Calculator/))

Feel free to interact with the project, browse through different jobs, and explore the user-friendly interface. The live demo provides a hands-on experience to see the Tabs Project in action.

## Contributing
If you have suggestions or find issues with the template, feel free to open an issue or create a pull request. Contributions are welcome!

## Contact
If you have any questions, feedback, or suggestions, please feel free to reach out to us at NourseenQandil@gmail.com We value your input and would love to hear from you!
