# ReduxReducerPractice
Codecademy assignment: Build a Redux Reducer for a Wagon Train game


## What Is It?
For this assignment, I was tasked with building a Redux reducer that changed the state of a Wagon Train game. I had to add an initial state with `supplies`, `distance`, and `days`. Then, I had to add actions such as `gather`, `travel`, and `tippedWagon`. As a bonus, I added the property of `cash`, then added the actions of `sell`, `buy`, and `theft`

## Why Did I Build This
I am beginning to learn about Redux and this is the stage of the module where we learned about actions and how a reducer function alters the state. When using Redux, I'm not supposed to change the initial state, and instead create a new variable using that state with a spread operator. Then, I can alter the new state variable which is what the function action returns.

## What I Found Challenging
I struggled a little with changing the state of an object, but quickly figured out how to copy the state object, then alter it using the types of actions. I really enjoyed this activity as it was straight forward and provided clear instructions on building the reducer function.

