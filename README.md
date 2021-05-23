# Multi-step form

Responsive multi-step form, I took it from https://codingnepalweb.com/multi-step-form-html-css-javascript/ and modified it so it can be responsive and adapt to any number of steps desired.

![Showcase image 1](img/showcase1.png?raw=true "Showcase 1")

## [Demo](https://multi-step-form-theta.vercel.app/)

## How to use

The project comes by default with 6 steps / 6 form pages, to add/remove steps you just have to modify the HTML, to add or remove steps in the progress bar, add or remove elements with class name "step". To add or remove form pages, add or remove elements with class name "page", the fist one must have the "slide-page" class. You must keep the same structure when adding or removing steps/pages.

**If number of steps is not equal to number of pages, there will be a warning on the console so you can know.**

## Validation

When user clicks next button, a simple validation is made, this is simple HTML validation getting triggered,
if input does not validate, it will add the "invalid-input" class, witch you can customize in the CSS. This validation only aplies to "input" fields, you may want to make your custom validation here, as well as when submiting the form to make it more reliable. I will try to make and update soon about this. Feel free to make a pull request if you want to code it yourself.
