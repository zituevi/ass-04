### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById sellects and changes the element by its id and an object can have a unique id of its own.

getElementsByClassName sellectes the element by class name, but many objects can have same class so they are also sellected.

querySelector sellects only the first matched element

querySelectorAll sellects all the matching elements found in the code.

### 2. How do you create and insert a new element into the DOM?

to create : let dib=document.createElement("div");
to add in dom : div.textContent="New Text";

### 3. What is Event Bubbling? And how does it work?
Event Bubbling starts from the target element and goes one step up instread of down. It goes from a button to its parent and then its parent,  like button--->div--->body etc.

### 4. What is Event Delegation in JavaScript? Why is it useful?

We can use event delegation instread of adding so many event listener, we can add one listener to the parent and control by bubbling.
it solves the problem of using too many event listener in the code .

### 5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() stops and blocks the default behaviour of any browser ,
stopPropagation stops the event bubbling.

