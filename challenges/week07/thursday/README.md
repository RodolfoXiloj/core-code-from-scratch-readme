<h2>Week challenges (Thursday) 💻</h2>

<h3>Convert a String to a Number! 📝</h3>

```js
const stringToNumber = function(str){
  // put your code here
  return parseInt(str);
}
```

</br>

<h3>Convert number to reversed array of digits 📝</h3>

```js
function digitize(n) {
  //code here  
  const digits = Array.from(String(n), Number);
  return digits.reverse();
}
```

</br>

<h3>Truthy and Falsy 📝</h3>

```js
const truthy = [1, 'hello', true, [], {}];;
const falsy = [0, '', false, null, undefined];

```

</br>

<h3>Training JS #4: Basic data types--Array 📝</h3>

```js
function getLength(arr){
  //return length of arr
  return arr.length
}
function getFirst(arr){
  //return the first element of arr
  return arr[0]
}
function getLast(arr){
  //return the last element of arr
  return arr[arr.length-1]
}
function pushElement(arr){
  var el=1;
  //push el to arr
  arr.push(el);
  return arr
}
function popElement(arr){
  //pop an element from arr
  if(arr.length >= 0)
    arr.pop();
  return arr
}
```
