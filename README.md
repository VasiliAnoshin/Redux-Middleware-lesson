## Project Setup

1. Clone the Project - git clone https://github.com/udacity/reactnd-redux-todos-goals.git
2. Go into the directory where the project now lives - `cd reactnd-redux-todos-goals`
3. Install the dependencies - `npm install`
4. Start the app - `npm start`

<h5>Questions :</h5>
<ul>
  <li>
     What is Redux middleware and what are some use cases for it?
    …a third-party extension point between dispatching an action, and the moment it reaches the reducer.
    What's great about middleware is that once it receives the action, it can carry out a number of operations, including:
    <ul>
      <li>producing a side effect (e.g., logging information about the store) </li>
      <li>processing the action itself (e.g., making an asynchronous HTTP request)</li>
      <li>redirecting the action (e.g., to another piece of middleware)</li>
      <li>dispatching supplementary actions</li>
    </ul>
  </li>
  <li>
     What is the relationship between middleware and the store?
  </li>
</ul>
