<h2>Week challenges (Wednesday) 💻</h2>

<h3>Count strings in objects 📝</h3>

```js
function strCount(obj){
// Your code here
  let count = 0;

  for (let key in obj) {
    if (typeof obj[key] === 'string') {
      count++;
    }
    else if (typeof obj[key] === 'object' && obj[key] !== null) {
      count += strCount(obj[key]);
    }
  }

  return count;
}
```

</br>

<h3>Extending JavaScript Objects: Get First & Last Array Element 📝</h3>

```js
// Write your code here...
Array.prototype.first = function() {
  return this[0];
}

Array.prototype.last = function(){
  return this[this.length - 1]; 
}
```

</br>

<h3>Object Oriented Piracy 📝</h3>

```js
//YOUR CODE HERE...
function Ship(draft,crew) {
 this.draft = draft;
 this.crew = crew;
}

Ship.prototype.isWorthIt = function() {
  if(( this.draft - (this.crew * 1.5)) > 20)
    return true
  else
    return false
}
```
