# Password-Generator

## What I need to do…

basically write code for these three functions `getPasswordOptions()`, `getRandom(arr)`, and `generatePassword()`

In order to get started I need to make psuedocode first…

### `getPasswordOptions()`

I need to prompt the user how many characters he wants between 10 and 64 characters in length

I have to think about character types… 

- Lowercase
- Uppercase
- Numeric
- Special characters ($@%&*, etc.)

That's it? So just collect user's inputs within an object.

### `getRandom(arr)`

This serves to get a random element from an array. Ok I need an array and generate a random index that matches an element of the array and return the value

### `generatePassword()`

…how? It seems like it needs to the two aforementioned functions.

Ok I need to create an empty array for the password…

obviously we would need to ask the user how long password he wants and what kind of character types he wants.

we then collect groups of these characters and put them in a different array

then we pick them randomly and put them in the password array.

And we mix them up so it's not in the order

And we turn it into a string…

Present it on HTML.