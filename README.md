## What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
 => ID names are unique, so by one ID we can get only one element. On the other hand, multiple elements can share the same class
    So getElementById and getElementsByClassName are different.
    querySelector selects the first element that matches a specified CSS selector and returns it in the form of a list. On the Other hand
    querySelectorAll selects all elements that match a specified CSS selector.

## How do you create and insert a new element into the DOM?
  => There are several ways to create new elements and insert them into the DOM. We can use document.cresteElement(). It can be a div or even a 
     whole section, then we must append that div to our desired parent Element.

## What is Event Bubbling and how does it work?
  => Bubbling is the mechanism of the DOM. Bubbling means that when an event is triggered, it will automatically trigger all those events that its 
     parent element had and goes on.

## What is Event Delegation in JavaScript? Why is it useful?
=> Attaching a single event listener to the parent element instead of attaching child elements

## What is the difference between preventDefault() and stopPropagation() methods?
=> Two separate JavaScript methods for controlling event behavior are preventDefault() and stopPropagation(), although they have different uses. 
   Where preventDefaults() is used to prevent the browser`s default actions, stopPropagation() is used to stop event bubbling.
   
