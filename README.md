# calculator
//Function to perform addition
function add(x, y) {
    return x + y;
}

// Function to perform subtraction
function subtract(x, y) {
    return x - y;
}

// Function to perform multiplication
function multiply(x, y) {
    return x * y;
}

// Function to perform division
function divide(x, y) {
    if (y === 0) {
        return "Cannot divide by zero!";
    }
    return x / y;
}

// Example usage
console.log("Addition: " + add(5, 3));
console.log("Subtraction: " + subtract(5, 3));
console.log("Multiplication: " + multiply(5, 3));
console.log("Division: " + divide(5, 3));
ator
