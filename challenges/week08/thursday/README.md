<h2>Week challenges (Thursday) 💻</h2>

<h3>Counting Duplicates 📝</h3>

```js
function duplicateCount(text){
  //...
  const charCount = {};
  const inputLowerCase = text.toLowerCase();
  let count = 0;

  for (const char of inputLowerCase) {
    if (/[a-z0-9]/i.test(char)) {
      charCount[char] = (charCount[char] || 0) + 1;
      if (charCount[char] === 2) {
        count++;
      }
    }
  }
  
  return count;
}
```

</br>

<h3>Encrypt this! 📝</h3>

```js
var encryptThis = function(text) {
  // Implement me! :)
  const words = text.trim().split(' ');
  
  const message = words.map(word=>{
    let encryptedWord = word.charCodeAt(0).toString();
    if(word.length >= 2)
      encryptedWord += word.length === 2 ? word[1] : word[word.length - 1] + word.substring(2, word.length - 1) + word[1];
    return encryptedWord;
  });

  return message.join(' ');
  
}
```

</br>

<h3>Valid Parentheses (retired) 📝</h3>

```js
function validParentheses(parens) {
  // your code here ..
  const stack = [];

  for (let i = 0; i < parens.length; i++) {
    const char = parens[i];
    if (char === '(') {
      stack.push(char);
    } else if (char === ')') {
      if (stack.length === 0 || stack.pop() !== '(') {
        return false;
      }
    }
  }
  
  return stack.length === 0;
  
}
```

</br>

<h3>Convert string to camel case 📝</h3>

```js
function toCamelCase(str) {
  var words = str.split(/[-_]/);
  var result = words[0];
  
  for (var i = 1; i < words.length; i++) {
    var capitalizedWord = words[i][0].toUpperCase() + words[i].slice(1);
    result += capitalizedWord;
  }

  return result;
}
```
