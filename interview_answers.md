# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

API context helps the components have access to the data or functions they require without have to set up connect.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions are functions that we pass a condition and a value, which is optional. Reducers are pure functions that take the current state and action and return the new state. Store is the object tree in Redux that is immutable. The store is known as a "single source of truth' because the only way to change the data is in the UI by using dispatch redux actions which will change state within redux reducer.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
   Redux-thunk allows us to call the action creators that return a function.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
   My favorite state management would have to be API Context when it comes to passing down data, but I would prefer Redux. Redux makes tracking our errors a lot simpler. Setting up the reducer with all of our logic helps us save time in the future when I need to make a new component and use the same logic in my reducer.
