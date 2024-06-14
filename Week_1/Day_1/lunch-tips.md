### Tips
Here is the code, using three of these ``` to designate it as javascript.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  console.log("I don't know what to do!");
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);

  if (hungry === false) {
    console.log("Wait until you are hungry!");
  } else {
    if (availableTime <= 20) {
      console.log("The answer is have a snack.");
    }
    if (availableTime > 20 && availableTime < 31) {
      console.log("The answer is cook a meal.");
    }
    if (availableTime > 30) {
      console.log("Maybe reconsider how much time you have first.");
    }
  }

};
console.log("I'm hungry and I have 20 minutes for lunch.");
whatToDoForLunch(true, 20);
console.log("-----");

console.log("I'm hungry and I have 50 minutes for lunch.");
whatToDoForLunch(true, 50);
console.log("-----");

console.log("I'm not hungry and I have 30 minutes for lunch.");
whatToDoForLunch(false, 30);
console.log("-----");

console.log("I'm hungry and I have 15 minutes for lunch.");
whatToDoForLunch(true, 15);
```