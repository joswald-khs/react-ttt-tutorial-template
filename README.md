# react-ttt-tutorial-template

We will be working from React's own [Quick Start: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe) tutorial with a few modifications.

## Getting Set Up

### Creating a Codespace
Your first step is to go to [GitHub Codespaces](https://github.com/codespaces), find the React card, and click `Use this template`. 

![Use this template](/screenshots/react_use_this_template.png)

This will create a virtual server for you directly on GitHub as well as a VSCode instance running in your browser editing the code on your server. Pretty neat. 

### Updating `App.jsx`

Now, copy the code that is in the `App.js` box in the tutorial and replace all the code *except* the code on line 1 (`import './App.css';`) of `App.jsx`

```jsx
import './App.css';

export default function Square() {
  return <button className="square">X</button>;
}
```
To see the results of all your hard work, you may need to do a bit of clicking around to get VSCode set up. The most straightforward way is to make sure that you have a bottom view. If you don't, click on this button in the upper-right part of the screen. 

![Bottom Panel](/screenshots/bottom_panel.png)

> [!TIP]
> You can also toggle this panel by pressing ctrl/cmd+J

Once that is open, select `PORTS` in the bottom panel that is now open. 

![Select Ports](/screenshots/select_ports.png)

Then, under `Forwarded Address`, hover over the link and select the split-screen icon. 

![Select Preview](/screenshots/select_preview.png)

You should now see an 'X' in a gray box! Wow!

### Updating `App.css`

As you progress through the first part of the tutorial, you'll get to a part where they are talking about a file called `styles.css`. If you look through your codespace files, you won't see it. You will see two other `css` files, though: `App.css` and `index.css`. Click on `App.css` and replace the contents with the following. 

> [!IMPORTANT]
> You really do need to replace everything here. 

```css
* {
  box-sizing: border-box;
}

body {
  font-family: sans-serif;
  margin: 20px;
  padding: 0;
}

h1 {
  margin-top: 0;
  font-size: 22px;
}

h2 {
  margin-top: 0;
  font-size: 20px;
}

h3 {
  margin-top: 0;
  font-size: 18px;
}

h4 {
  margin-top: 0;
  font-size: 16px;
}

h5 {
  margin-top: 0;
  font-size: 14px;
}

h6 {
  margin-top: 0;
  font-size: 12px;
}

code {
  font-size: 1.2em;
}

ul {
  padding-inline-start: 20px;
}

* {
  box-sizing: border-box;
}

body {
  font-family: sans-serif;
  margin: 20px;
  padding: 0;
}

.square {
  background: #fff;
  border: 1px solid #999;
  float: left;
  font-size: 24px;
  font-weight: bold;
  line-height: 34px;
  height: 34px;
  margin-right: -1px;
  margin-top: -1px;
  padding: 0;
  text-align: center;
  width: 34px;
}

.board-row:after {
  clear: both;
  content: '';
  display: table;
}

.status {
  margin-bottom: 10px;
}
.game {
  display: flex;
  flex-direction: row;
}

.game-info {
  margin-left: 20px;
}
```

Once you do this, you should see the 'X' change to being slightly larger, having a white background, and being in a slightly different location.

### Finising the tour. 

You'll see a reference to looking at `index.js`, but like above, the code is actually in a file called `index.jsx`. It might not be _exactly_ the same, but it should be pretty close. You can read that it is more connective code.
