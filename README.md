DeckAsStack
===========

Treats the cards[] array in the constructor function Deck() as the data type stack.

The data structures we covered in class for this assignment (e.g. stack and queue) don't seem to be native to JS. Rather,
it seems the only way to implement a stack is to simply treat a regular array as a stack by only using push/pop methods on it.

For this assignment I decided to treat the cards[] array in the Deck() object as a LIFO stack. Since the shuffle method requires
accessing elements of the array that are not on top, I moved the shuffle method inside the build() function of the constructor class
Deck(), and from then on out treat the array as a stack.

I'm not very confident I interpreted this assigmnet correctly, so please let me know how I could have done this better.
