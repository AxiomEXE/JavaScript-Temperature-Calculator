# JavaScript-Temperature-Calculator
A Temperature Calculator
```markdown
const kelvin = 273;
//The forecast today is constant.
let celsius = kelvin - 273;
//Celsius is 273 less than Kelvin.
let fahrenheit = celsius * (9/5) + 32;
//The above is how you calculate Fahrenheit.
Math.floor(fahrenheit);
//This rounds down Fahrenheit's number.
let newton = celsius * (33/100);
Math.floor(newton);
Math.floor(celsius);
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`);
console.log(`The temperature is ${celsius} degrees Celsius.`);
console.log(`The temperature is ${kelvin} degrees Kelvin.`);
console.log(`The temperature is ${newton} degrees Newton.`);
```
