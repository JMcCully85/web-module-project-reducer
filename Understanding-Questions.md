# Understanding Questions:

What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
The user presses the 1 button.
On click calls handler function
handler function calls dispatch with addOne() which is of type ADD_ONE
the ADD_ONE case then returns sate with the change of total being incremented
the change of state rerenders the component
TotalDisplay shows the total plus 1.
