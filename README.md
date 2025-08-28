I have to create a `Readme.md` file. and write down following questions.

### 6. Answer the following questions clearly:

💕1. What is the difference between **getElementById, getElementsByClassName, and
   querySelector / querySelectorAll**?
   ✔ Ans-The key differences between getElementById, getElementsByClassName, and querySelector/querySelectorAll
   are-

1.getElementById are uses for selecting a single element by its unique ID.
2.getElementsByClassName are uses when i need a live collection of elements
sharing a class name.
3.querySelector will be uses when i need the first element
matching a CSS selector.
4.querySelectorAll are uses when i need a static
collection of all elements matching a CSS selector.

💕2. How do you **create and insert a new element into the DOM**?

 ✔ Ans: The DocumentObject Model (DOM) is a programming interface for web documents.
   Itrepresents the page so that programs can change the document
   structure,style, and content To create and insert a new element into the DOM,
   we follow these steps:
   step-01: Use createElement() to create a new element.
   step-02:Use setnsttribute() to set any needed attributes such as id or class.
   step-03:Use createTextNode() to create the content.
    step-04: Use appendChild() to attach the text node to the element and insert it into the
   DOM.

Example:

let newDiv = document.createElement("div"); newDiv.setAttribute("id", "myDiv");
let text = document.createTextNode("Hello World!"); newDiv.appendChild(text);
document.body.appendChild(newDiv). 

💕3. What is **Event Bubbling** and how does it
work?

✔ Ans:Event bubbling in JavaScript is a mechanism where an event, after being
triggered on a specific target element, propagates upwards through its ancestor
elements in the Document Object Model (DOM) tree. This process continues until
the event reaches the root of the document, or unless it is explicitly
stopped.

💕 4. What is **Event Delegation** in JavaScript? Why is it useful?
✔ Ans:Instead of adding an event listener to every child, we put one on the parent and
let it handle events for all children (works because of event bubbling).


💕 5. What is the difference between **preventDefault() and stopPropagation()**
   methods?
   ✔ Ans:
 preventDefault() → stops the browser’s default action (like
   opening a link).
stopPropagation() → stops the event from bubbling up to parent elements.

