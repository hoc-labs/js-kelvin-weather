# Kelvin Weather

Deep in his mountain-side meteorology lab, the mad scientist Kelvin has mastered weather prediction.

Recently, Kelvin began publishing his weather forecasts on his website. However there’s a problem: All of his forecasts describe the temperature in [Kelvin](https://en.wikipedia.org/wiki/Kelvin).

With our knowledge of JavaScript, let’s convert Kelvin to Celsius, then to Fahrenheit.

![Kelvin, Celsius, and Fahrenheit thermometers](https://raw.githubusercontent.com/hoc-labs/images/main/Kelvin%20Thermometers.svg)

For example, 283 K converts to 10 °C which converts to 50 °F.

The forecast today is `293` Kelvin. 

## Step 1

To start, create a variable named `kelvin`, and set it equal to `293`.

The value saved to `kelvin` will stay constant. Choose the variable type with this in mind.

Celsius is similar to Kelvin — the only difference is that Celsius is `273` degrees less than Kelvin.

## Step 2

Convert Kelvin to Celsius by subtracting `273` from the `kelvin` variable. 

Store the result in another variable, named `celsius`.

Use this equation to calculate Fahrenheit, then store the answer in a variable named `fahrenheit`.

_Fahrenheit = Celsius \* (9/5) + 32_

In the next step we will round the number saved to `fahrenheit`. 

Choose the variable type that allows you to change its value.

## Step 3

When you convert from Celsius to Fahrenheit, you often get a decimal number.

Use the `.floor()` method from the built-in Math object to round down the Fahrenheit temperature. Save the result to the `fahrenheit` variable.

Here's a [reference](https://education.launchcode.org/intro-to-professional-web-dev/appendices/math-method-examples/ceilfloortrunc-examples.html#floor) for the Math.floor method.

## Step 4

Use `console.log` and string interpolation to log the temperature in `fahrenheit` to the console as follows:

```
The temperature is TEMPERATURE degrees Fahrenheit.
```

Use string interpolation to replace `TEMPERATURE` with the value saved to `fahrenheit`.


## Step 5

Run your program to see your results!

By using variables, your program should work for any Kelvin temperature — just change the value of `kelvin` and run the program again.

What’s `0` Kelvin in Fahrenheit?


Great work! Kelvin can now publish his forecasts in Celsius and Fahrenheit.

If you’d like extra practice, try this:

* Convert `celsius` to the [Newton](https://en.wikipedia.org/wiki/Newton_scale) scale using the equation below

_Newton = Celsius \* (33/100)_

* Round down the Newton temperature using the `.floor()` method
* Use `console.log` and string interpolation to log the temperature in `newton` to the console**.**




