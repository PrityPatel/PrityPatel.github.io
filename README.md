
# The Fortune Memory Game

  - A Memory Game Where Individual Focus Leads to a Customized Fortune!


## Game Description:

  - The premise of this game was a combination a game (Memory or Concentration) with an interactive user experience (getting a prediction when clicking a button).

    - The game: Sometimes called "Memory" or "Concentration", it's a card game in which all of the cards are laid face down on a surface and two cards are flipped face up over each turn. If you get all the matching cards, you've won! The Fortune Memory Game incorporates this by allowing a player click on 2 sqaures at a time and seeing if they are a match, if not, then trying again.

    - The user experience: People like the experience of getting a fortune cookie or reading their horoscopes online. The Fortune Memory Game incorporates this by tying the fortune cookie message to the amount of attempts it took a player to complete or match all sqaures on the board, hence, their "Fortune" message is directly tied to their "Focus" on the game.


## Technologies Used:

  - HTML was used for the structure of the webpage
  - CSS used for styling of the webpage
  - jQuery was used for DOM Manipulation
  - Javascript was used for game logic



## Design Approach:

  - **Webpage:**

    - In designing the webpage for this game, the approach was to incorporate minsimalism and elements of balance and simplicity. The design incorporated elements of a feng shui bagua, a Chinese religious motif incorporating the eight trigrams of the I Ching, with colors typically arranged octagonally around a symbol denoting the balance of yin and yang.

    - Each color in the bagua represents different elements. For this game, I utilized:
        - Purple, considered to be the color of abundance and prosperity
        - Gray, considered to be the color of helpful sources and movement
        - Black, considered to be the color of water and flow
        - White, considered to be the color of metal and balance


## Installation Instructions (Getting Started):

  - **To Play:**

    - Open the browser of your choice on your computer or mobile device and navigate to:
    `http://pritypatel.github.io/`.

    - Start clicking on the purple squares in the box. Once you have matched all the squares, an alert will appear with your Fortune Number.

    - Take note of your Fortune Number and then scroll down to read the Fortune associated with your Fortune Number.

    - Refresh the page and play again for another Fortune Number and Fortune.

  - **To Contribute or View Code and Source Files:**

    - Create a copy or `Fork` of this repo. Do so by clicking the `Fork`  button that is located above on the right corner of this page. By forking this repo, you will now have a full working copy of all the same source files, issues, and commit history that currently exists in this repo.

    - Next, to work on the code, you'll need to make a local copy of the fork. To make a local copy of the forked repo, you'll need to open up your computer Terminal and navigate to the directory where you would like to store the repo and work on it. Make sure you store it in a directory where you already have created a git directory via `git init`, otherwise, `git init` first.

    - Once you've navigated (via the Terminal) to the directory where you would like to save the working files, go ahead and then type: `git clone https://github.com/PrityPatel/Memory-Game.git` and follow the instructions. You may be prompted for your Github login credentials.

    - You now have a local copy on your computer and a remote copy on Github. Open the local files in your favorite text editor, such as Sublime Text.


## Unsolved problems & issues and/or planned features:

  - **Issues:**

    - Matched items are currently reclickable: matched items should not be clickable again until board is reset.

    - Board should reset after all 6 matches have been made/found

  - **Planned Features:**

    - Adding in Customized Fortunes

    - Adding in a 2 player option

    - Adding a Fortune Number display that displays number of clicks on the board

    - Adding in a personalized message to the player

    - Adding in a game over message

    - Adding in a reset button and function to reset the game


## User Stories:

  **MVP:**

  - [x] As a player, I would like to see the title of the game on the page, so I know what the game is.

  - [x] As a player, I would like to see the images of the cards I click on, so I know if I matched the cards.

  - [x] As a player, I would like to only see the images on the cards when I click on them, so that the game isn't played for me.

  - [x] As a player, I would like to only be able to click on a maximum of 2 cards at one time, so that I can play another turn.

  - [x] As a player, I would like to see the cards kept face up if I matched, so that I know what cards I should not click on again.

  - [x] As a player, if the images don't match, the cards should only stay revealed for a max of 10 seconds, before being hidden again, so that I know which cards can be played again.

  - [x] As a player, I would like to see something when the game is over or I have completed the board, because it provides for completion.

  - [x] As a player, I would like to get feedback on what to do next once I have completed the board.

  - [ ] As a player, I would like to see good Fortune descriptions written.

**Icebox:**

- [ ] As a player, I would like to see a 'score' to see how many attempts I have made thus far, so that I can see progress.

- [ ] As the computer, I would like to know your name, so I can personalize messages to the player.

- [ ] As a player, I would like to see my messages personalized with my name, so I feel special.

- [x] As a player, I would like to win or unlock a prize once the board is complete, because it provides incentive.


