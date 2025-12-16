# react-ttt-tutorial-template

We will be working from React's own [Quick Start: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe) tutorial with a few modifications.

Your first step is to go to [GitHub Codespaces](https://github.com/codespaces), find the React card, and click `Use this template`. 

![Use this template](/screenshots/react_use_this_template.png)

This will create a virtual server for you directly on GitHub. 

Now, copy the code that is in the `App.js` box in the tutorial and replace all the code *except* the code on line 1 (`import './App.css';`) of `App.jsx`

```jsx
import './App.css';

export default function Square() {
  return <button className="square">X</button>;
}
```
