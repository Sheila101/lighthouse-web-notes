# Sheila's Notes

## Summary

#### This repository contains all of the notes taken by [Sheila](https://infrotrade.netlify.app/) for the Lighthouse Labs Web Development Bootcamp.

- [Week 1](/Week_1)

  - [Day 1](/Week_1/Day_1)

  ```javascript
  const whatToDoForLunch = function (hungry, availableTime) {
    //console.log("I don't know what to do!");
    if (hungry === true && availableTime <= 20) {
      console.log(
        'Pick up a snack or grab something already cooked in the fridge'
      );
    } else if (hungry === true && availableTime < 30) {
      console.log('You deserve a break, you should cook something tasty');
    } else if (hungry === true && availableTime > 30) {
      console.log('This is an intense program, you should reconsider');
    } else {
      console.log('Wait until you are hungry');
    }
  };
  ```
