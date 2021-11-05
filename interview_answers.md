# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

It makes it so we do not need to use prop-drillin and on more complicated applications can more easily manage state without running into bugs.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

actions store information for the reducer, reducers take in the previous state of the application and return a new state using the actions, and store holds the application state. 

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

it allows us to call on the action creators and return a function, so we now wright action creators that return functions instead of actions.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

I like the implimentation of thunk because it makes it easier to properly use dispatch in different situations.