Answer the following questions clearly:

1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

   Ans: getElementById returns a single element based on a unique ID attribute; getElementsByClassName returns an HTMLCollection of elements with a specified class name; querySelector returns the first element that matches the CSS selector; and querySelector returns a NodeList of elements that match the CSS selector.

2. How do you create and insert a new element into the DOM?

   Ans:Create a new element using document.creteElement('element_name') Example: document.creteElement('div').(Optional) Set attribute of an element using element.setAttribute('property_name', 'value'). Example: myElement.setAttribute('title', 'This is my element').Select it's parent using document.getElementById('id').Use parentElement.appendChild(newElement) to add the newly created element to the parent element.

3. What is Event Bubbling and how does it work?

   Ans: Event Bubbling is a technique that spreads among parent elements. When an event occurs on a child element, it "bubbles" up to the parent, grandparent, and so on until it reaches the root element. This is the process of event bubbling.

4. What is Event Delegation in JavaScript? Why is it useful?

   Ans: Event Delegation is a method for effectively managing events. It entails adding a single event listener to a parent element rather than separate event listeners to each element. It makes code cleaner, more readable, and easier to manage, which makes code maintenance for dynamically added new elements easier.

5. What is the difference between preventDefault() and stopPropagation() methods?

   Ans: The preventDefault() function stops an element from doing something, like submitting a form or going to a new page when clicked on a link. The stopPropagation() function stops an event from moving up or down the DOM Tree, which stops parent or child elements from handling the same event.
