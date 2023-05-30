<h2>Week challenges (Monday) 💻</h2>

<h3>Training JS #7: if..else and ternary operator! 📝</h3>

```js
function saleHotdogs(n){
  var price = 0;
  if(n<5)
    price = 100 * n
  else if(n>=5 & n<10)
    price = 95 * n
  else if(n>=10)
    price = 90 * n
  
  return price;
}
```

</br>

<h3>Training JS #8: Conditional statement--switch 📝</h3>

```js
function howManydays(month){
  var days;
  switch (month){
    case 1: case 3: case 5: case 7: case 8: case 10: case 12:
      days = 31  
      break;
    case 4: case 6: case 9: case 11:
      days = 30
      break;
    case 2:
      days = 28;
      break;  
  }
  return days;
}
```

</br>

<h3>Basic Calculator 📝</h3>

```js
function calculate(num1, operation, num2) {
 //TODO: make a basic calculator.
  var result = null;
  switch(operation){
      case "+":
        result = num1 + num2;
        break;
      case "-":
        result = num1 - num2;
        break;
      case "*":
        result = num1 * num2;
        break;
      case "/":
        if(num1 === 0 || num2 === 0)
          result = null;
        else
          result = num1 / num2;
        break;
      default:
        break;
  }
  
  return result;
}
```
