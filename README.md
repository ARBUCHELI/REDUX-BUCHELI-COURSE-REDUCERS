# REDUX-LESSONS-INSTRUCTOR-ANDRES-R.-BUCHELI

## Usage:
* Creating a reducer function.
* A reducer, or reducer function, is a plain JavaScript function that defines how the current state and an action are used in combination to create the new state.

## There a few things about this reducer that are true for all reducers:

* It’s a plain JavaScript function
* It defines the application’s next state given a current state and a specific action
* It returns a default initial state if no action is provided
* It returns the current state if the action is not recognized

## There are two intermediate JavaScript syntaxes used here:

* We use the equals sign = to supply a default value for the state parameter.
* We use the spread operator (...) to copy the current state and any changed values into a new object, not the existing state argument. We’ll explain why in the next exercise.
