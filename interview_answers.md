# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    Context API helps to solve issues with moving props from parent to child or grandparent to child and is typically the easier to use state management practice.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Actions are are a source of data that carries a payload of information to be stored. Reducer is a function that takes the current state and an action to return an updated state object based on what was provided.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    Redux-thunk allows you to call action creators that return a function. It changes action creators because it can be used to delay an action or make an action only occur if a specific parameter is met.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    Redux is my favorite state management system because it is the most in depth and functional in my opinion. You have a lot of flexibility with redux which can be very useful.