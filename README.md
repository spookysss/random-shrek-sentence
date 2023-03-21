# Random Shrek sentence
Funny script that returns a random Shrek sentence

# How to use
```js
const req = fetch('https://raw.githubusercontent.com/spookysss/random-shrek-sentence/main/random.js').then((response) => response.text());
  
req.then((data) => eval(data + "\nshrekSentence();")).then(function(result) {
	console.log(result);
	return result;
})

```
