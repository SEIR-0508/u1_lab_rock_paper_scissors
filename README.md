## SEIR 0508

<img src="https://i.imgur.com/cIz3Qx8.png">

# Build Another Game - Rock Paper Scissors

## Intro

Before heading off to start work on your Project 1, let's write another browser-based game together from start to finish (hopefully).

We'll get practice building the the UI using HTML & CSS and coding the game-play with JavaScript.


#### This Code Along is a Deliverable

## Key Points From the "Guide"

Before we start coding Rock-Paper-Scissors, let's review some KEY CONCEPTS of the Guide on How to Build a Browser Game...

### Data-Centric Approach

Data (state) is the single-source of truth of any application!

The visualization of that data is secondary to the data and the logic that manipulates it.

### The `init()` Function

The `init()` function's responsibility is to initialize all state.

`init()` will be called when the program loads to initialize the state (data).

In many cases `init()` can also be provided as the callback handler function for the [Play Again] button!

Typically, the last line of code in the `init()` function is a call to `render()`...

### The `render()` Function

The render() function is responsible for rendering ALL state to the DOM.

We don't modify/update the DOM elements outside of render functions.

> There are very few exceptions to this rule. One exception might be if you wanted to render an "ticking timer" - in this case, it would be fine to update the DOM outside of the normal render function(s).

### When the User Interacts With the App...

In response to user interaction, such as when a user clicks something, the event handler function's responsibility is to:

1. Update all impacted state (data)
2. Then, call `render()`

## Wireframes

We're going to go with a clean, minimal user interface.

> Note: Feel free to go with your own layout, colors, etc. as we code this app.

Upon loading, the UI should look something like the following wireframe:

<img src="https://i.imgur.com/Xq6Ar1L.png">

Upon clicking the **Rock, Paper, Scissors... Go!** button, there will be a small display that counts down 3, 2, 1...:

<img src="https://i.imgur.com/LbUq0Ia.png">

After the countdown finishes, the scores will be updated; and if there's a winner, that symbol will be rendered with a grey border:

<img src="https://i.imgur.com/mJe7SQW.png">

## Setup

So that we don't have to spend too much time typing in HTML & CSS, we have some starter code...

Please open this RPS - [Starter Code repl](https://replit.com/@SEIStudent/RPS-Starter-Code#index.html)

Included along side this README file are starter versions of:
- `index.html`
- `css/main.css`
- `js/main.js`
- An `imgs` folder containing the three RPS images

## Code Along

As we code together, for the most part, we'll follow this guidance:

1. Identify and initialize state variables.
2. Code the main `render()`, `renderScores()` & `renderResults()` functions.
3. Code the click event listener, including the win logic.
4. Update the `renderResults()` function to render the winner border.
5. Code the countdown timer.

## Submit Your Repl

This code along is a deliverable, please move to the next page and submit the link to your RPS Repl.


