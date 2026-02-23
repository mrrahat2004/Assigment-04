1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Answer:
getElementById - It only finds elements with a specific ID. Since a page can have an ID only once, it returns only one element.

getElementsByClassName - It returns all elements with specific Class Name as a list.

querySelector - It is much more flexible. You can find the first element that matches with the ID, class or tag, similar to CSS.

querySelectorAll: It works the same as querySelector, but it returns all elements matching that selector as a list.


2. How do you create and insert a new element into the DOM?
Answer:
to create use createElement('div')
to insert use document.appendChild()

3. What is Event Bubbling? And how does it work?
Answer:
Event Bubbling is how events propagate through the DOM.

4. What is Event Delegation in JavaScript? Why is it useful?
Answer:
Event Delegation is a pattern where you attach a single event listener to a parent element instead of attaching many listeners to individual child elements.

it's useful:

1.Memory Efficiency: One listener uses less memory than 100.

2.Dynamic Elements: If you add new buttons to a list via JavaScript, they automatically have the click functionality because the parent is already watching for them.


5. What is the difference between preventDefault() and stopPropagation() methods?
Answer:
preventDefault(): Stops the browser's default action.
stopPropagation(): Stops the event from bubbling up.