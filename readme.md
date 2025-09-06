

### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Ans: getElementById(): Returns a single element with the specific Id .
getElementsByClassName(): Returns all elements that have a specific class name.
querySelector(): Returns the first element for match  CSS selector.
querySelectorAll(): Returns a  NodeList of all elements that match a CSS selector.

2. How do you **create and insert a new element into the DOM**?
Ans: 
Create : const div = document.createElement("div");
Modify : div.innerText = "Hello"; div.classList.add("box");
Insert :parent.appendChild(div); 

3. What is **Event Bubbling** and how does it work?
Ans :Event Bubbling means when an event occurs on a child element, it also triggers on its parent elements.
For example- if i click a button inside a card, the button event runs, and the card event also gets triggered.

4. What is **Event Delegation** in JavaScript? Why is it useful?
Ans:Event delegation is a technique where you attach a single event listener to a parent element to handle events from multiple child elements, leveraging event bubbling.

5. What is the difference between **preventDefault() and stopPropagation()** methods?
Ans:
preventDefault() :It Stops the default browser action of an element.
stopPropagation() → It Stops event bubbling, meaning the event will not propagate to the parent elements.
