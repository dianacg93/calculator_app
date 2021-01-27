# Calculator App
Today you will be building a calculator with React.
Steps
Start by creating a single component name it Calculator.jsx. Create your Calculator component and in your return statement add the following:
```
<div className="container">
  <h1>Add with React!</h1>

  <form className="add">
    <input type="text" name="value1" />
    <span>+</span>
    <input type="text" name="value2" />
    <span>=</span>
    <h3>Addition results go here!</h3>
  </form>
</div>
```
Set up the initial state of your component. What state will you need to track? What values should those state items start with? Where is that state printed to the browser?

You will need to figure out how and when you want to listen for an event to trigger a calculation. Is it a click event, a submit event...? It's up to you to figure out what event you want to listen for, on which elements, and why. Here is a list of events React supports.

Once you know what event to listen for, you'll need to create a method that accepts the triggered event, gets the input values from your form, adds them together, and sets the state of the new sum.
thought: how will you handle inputs that aren't numbers?

Once the state of the sum has been set, React will re-render the whole component. Make sure you have a place in your JSX that displays the result!

Make the calculator work with any of the 4 basic arithmetic operations (+, -, *, /). How will this change your state, and your JSX?
Style using Flexbox or CSS Grid.

### Bonus
Create a mobile version of this using media queries
Use touch events
MDN Touch Events
