# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project?
-   How will you use version control to backup / track your project?
-   Do you plan to attempt any of the bonuses?

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).

**The data structure you plan to use**

I know I'll at least need a `Game`, `Board` and `Player` for the game logic. For authentication I'll follow a similar pattern to what we went over in the ajax lessons to seperate concerns

**A wireframe of what your game project will look like**

See `tic-tac-toe.pdf`

**How you will take the markup of the game board and represent it in JS?**

To get the markup of the board I'll use jQuery to get the value of each element on the gameboard and then create an array which represents the 9 slots on the board.

**How you plan to approach this project?**
I'll begin the project by planning my game logic since it's the most difficult and core piece of the app. Then I'll begin plan any other pieces such as the authentication. When I being coding I'll move in this order:
- HTML Markup
- Styling
- Game Logic
- Helper Logic (reset button, etc..)
- Authentication
- Documentation

**How you plan to keep your code modular?**
To keep my code modular by seperating things related to authentication, the ui and the game logic in seperate folder and files.

**What creative spin will you add to your project?**
If I can finish a two player game in ample time I may try to implement a 1 player game using the [Minimax  Algorithm](https://en.wikipedia.org/wiki/Minimax).

**How will you use version control to backup / track your project?**
I plan to use git early and often in this project. Anytime I accomplish a task like completion of a function I will use git to save my changes.

**Do you plan to attempt any of the bonuses?**
I will only go for bonuses if and when I have a working game that meets all of the project requirements. If I do go for a bonus I think I'll likely try to save games using local storage.
