<h2>Week challenges (Wednesday) 💻</h2>

<h3>Who likes it? 📝</h3>

```js
function likes(names) {
  // TODO
  switch(names.length){
      case 0:
        return 'no one likes this';
      case 1:
        return `${names[0]} likes this`;
      case 2:
        return `${names[0]} and ${names[1]} like this`;
      case 3:
        return `${names[0]}, ${names[1]} and ${names[2]} like this`;
      default:
        const othersCount = names.length - 2;
        return `${names[0]}, ${names[1]} and ${othersCount} others like this`;
  }
}
```

</br>

<h3>Bit Counting 📝</h3>

```js
var countBits = function(n) {
  let count = 0;
  let binary = n.toString(2);

  for (let i = 0; i < binary.length; i++) {
    if (binary[i] === '1') {
      count++;
    }
  }

  return count;
};
```

</br>

<h3>Your order, please 📝</h3>

```js
function order(words){
  // ...
  const wordsArray = words.trim().split(' ');
  const sortedWords = [];

  for (let i = 1; i <= wordsArray.length; i++) {
    for (const word of wordsArray) {
      if (word.includes(i)) {
        sortedWords.push(word);
      }
    }
  }

  return sortedWords.join(' ');
}
```
