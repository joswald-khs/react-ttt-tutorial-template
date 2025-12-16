# react-ttt-tutorial-template

We will be working from React's own [Quick Start: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe) tutorial with a few modifications.

## Getting Set Up
Your first step is to go to [GitHub Codespaces](https://github.com/codespaces), find the React card, and click `Use this template`. 

![Use this template](/screenshots/react_use_this_template.png)

This will create a virtual server for you directly on GitHub as well as a VSCode instance running in your browser editing the code on your server. Pretty neat. 

Now, copy the code that is in the `App.js` box in the tutorial and replace all the code *except* the code on line 1 (`import './App.css';`) of `App.jsx`

```jsx
import './App.css';

export default function Square() {
  return <button className="square">X</button>;
}
```
To see the results of all your hard work, you may need to do a bit of clicking around to get VSCode set up. The most straightforward way is to make sure that you have a bottom view. If you don't, click on this button. 

![Bottom Panel](/screenshots/bottom_panel.png)
