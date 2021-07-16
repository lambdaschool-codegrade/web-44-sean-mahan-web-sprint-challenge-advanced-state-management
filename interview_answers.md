# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
  Context API is a good middle ground between pure react and redux, giving a central location to make it easier to have fluidity with constant things like themes without prop drilling and having a lot less leg work than redux
2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
  actions: different things you can do to change the state of an application that gets triggered by user input, or linear run-through of a part of an application
  reducers: where actions are sorted through to actually change the state
  store: the global place to gain access to props
3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
  It allows you to interact with things that take a unit of time to use, compared to only having a unit of time per function
4. What is your favorite state management system you've learned and this sprint? Please explain why!
  I really like useContext because it feels nice and simple, but I feel like eventually I'll find more love for redux because of the results