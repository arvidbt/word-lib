# wordlib 📚
[![Test](https://github.com/arvidbt/wordlib/actions/workflows/test.yml/badge.svg)](https://github.com/arvidbt/wordlib/actions/workflows/test.yml/badge.svg)



Small package for playing around with Swedish-and English words and abbreviations.

## Installation 📦
To use the package, first install it:
```bash
TODO.
```
Then, import it as:
```javascript
import { WordLib } from "wordlib";
```
Instantiate the class:
```javascript
// For English,
const enWords = new WordLib({language: "en"});
// For Swedish,
const svWords = new WordLib({langugage: "sv"});
// For custom dictionary,
const customWords = new WordLib({customDictionary: ["custom", "dictionary"]});
```
Now, you're ready to use wordlib for your own applications 🚀.

## Usage 📖
For documentation, visit [the official documentation](https://arvidbt.github.io/wordlib/).

The functions can be used in conjunction with eachother, such as:
```javascript
const enWords = new WordLib({language: "en"});
const randomPalindrome = enWords.random({customDictionary: enWords.palindromes()});
```