<h2>Week challenges (Tuesday) 💻</h2>

<h3>Even or Odd 📝</h3>

```js
function evenOrOdd(number) {
  if ((number % 2) === 0)
    return "Even";
  else
    return "Odd";
}
```

</br>

<h3>A wolf in sheep's clothing 📝</h3>

```js
function warnTheSheep(queue) {
  number = queue.length;
  animalPast = "";
  result = "";
  queue.map(function(animal, index){
    if(animal != "wolf")
        number--;
    
    if((index + 1) === queue.length && animal === "wolf")
      result = "Pls go away and stop eating my sheep";
    else if(animalPast === "wolf")
      result = "Oi! Sheep number "+number+"! You are about to be eaten by a wolf!";
    
    animalPast = animal;
  });
  
  return result;
} 
```

</br>

<h3>Decode the morse code 📝</h3>

```js
decodeMorse = function decodeMorse(morseCode) {
  const morseCodeMap = {
    '.-': 'A', '-...': 'B', '-.-.': 'C', '-..': 'D', '.': 'E',
    '..-.': 'F', '--.': 'G', '....': 'H', '..': 'I', '.---': 'J',
    '-.-': 'K', '.-..': 'L', '--': 'M', '-.': 'N', '---': 'O',
    '.--.': 'P', '--.-': 'Q', '.-.': 'R', '...': 'S', '-': 'T',
    '..-': 'U', '...-': 'V', '.--': 'W', '-..-': 'X', '-.--': 'Y',
    '--..': 'Z', '.----': '1', '..---': '2', '...--': '3',
    '....-': '4', '.....': '5', '-....': '6', '--...': '7',
    '---..': '8', '----.': '9', '-----': '0', '...---...': 'SOS',
    '-.-.--': '!',
    '.-.-.-': '.'
  };

  const words = morseCode.trim().split('   ');
  const decodedWords = words.map(word => {
    const letters = word.split(' ');
    const decodedLetters = letters.map(letter => {
      if(letter in morseCodeMap)
        return morseCodeMap[letter];
      return letter;
    });
    
    return decodedLetters.join('');
  });

  return decodedWords.join(' ');

}
```
