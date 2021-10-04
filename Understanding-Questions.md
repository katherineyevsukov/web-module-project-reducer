# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The handleNumberClick function is fired, taking in 1 as an argument
* 1 is passed in to the applyNumber action creator and returns ({type:APPLY_NUMBER, payload: 1}) which is passed into the reducer function through dispatch
* The switch statement matches to the appropriate type, makes a copy of the state and updates the total +1
...

* TotalDisplay shows the total plus 1.
