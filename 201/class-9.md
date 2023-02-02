# Class 9 Notes

## Html

1. Why are forms so important in web development?

-they are used for collecting data from users, or allowing them to control a user interface. One of the main points of interaction between a user and a website or application. 

2. When designing a form, what are some key things to keep in mind when it comes to user experience? 

-Help our users fill out our forms correctly and not get frustrated when trying to use our apps. The bigger your form, the more you risk frustrating people and losing users. Keep it simple

3. List 5 form elements and explain their importance.

- Form
This element formally defines a form. It's a container element specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes:

- label
For usability and accessibility, we include an explicit label for each form control. it associates the label with the form control, enabling mouse, trackpad, and touch device users to click on the label to activate the corresponding control, and it also provides an accessible name for screen readers to read out to their users. 

- text area
It represents a basic single-line text field that accepts any kind of text input.

- button
button to allow the user to send, or "submit", their data once they have filled out the form. 

# Js

1. How would you describe events to a non-technical friend?

- events are like paying for food. you pay the food is returnded but not until you pay. or like having a newborn you listen to for cries and then you go and give the baby what it needs, but not all the time because then the baby will learn how to drive you crazy. different, but same.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

- the name of the event and a function to handle the event. So we call the button's addEventListener() method

3. Describe the event object. Why is the target within the event object useful?

- block of code that runs when the event fires. When such a block of code is defined to run in response to an event, we say we are registering an event handler. 

4. What is the difference between event bubbling and event capturing?

- Event bubbling describes how the browser handles events targeted at nested elements.
This is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.



## Sources
[html forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[web forms](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[web form structure](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

[events in JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

## Things I want to know more about

- event capture
- everything about forms, they seem really complicated.