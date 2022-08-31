<p align="center" width="100%">
    <img src="https://github.com/agusle/nba-players-predictions/blob/main/img/project-logo-nba.png">
</p>

<p align="center">
    <a href="https://github.com/agusle/nba-players-predictions/commits/main">
    <img src="https://img.shields.io/github/last-commit/agusle/nba-players-predictions?logo=Github"
         alt="GitHub last commit">
    <a href="https://github.com/agusle/nba-players-predictions/issues">
    <img src="https://img.shields.io/github/issues-raw/agusle/nba-players-predictions?logo=Github"
         alt="GitHub issues">
    <a href="https://github.com/agusle/nba-players-predictions/pulls">
    <img src="https://img.shields.io/github/issues-pr-raw/agusle/nba-players-predictions?logo=Github"
         alt="GitHub pull requests">
</p>

<p align="center">
    <a href="#-introduction---analysis-of-nba-players-in-the-20212022-season">Introduction</a> •
    <a href="#-about">About</a> •
    <a href="#%EF%B8%8F-install-and-run">Install and Run</a> •
    <a href="#-contribute">Contribute</a> •
</p>

------------------
## 🏀 Introduction - Analysis of NBA players in the 2021/2022 season

The National Basketball Association is the main basketball league in the United States of America. It currently features 30 teams from different cities, divided in 2 conferences (East and West) of 15 teams. Each team plays a total of 82 games during the regular season. After that, the 8 teams with better records from each conference are seeded in a playoff format, with the winner of each conference playing the finals to determine the eventual champion. NBA seasons usually play out between october of one year, to june of the next year, so for example the current season being played is called the 2021/2022 season.

As in most leagues in the world, the game is played 5 vs 5 players, with as many as 9 reserve players that can rotate with the starters as many times as the team wants. Games are played to 48 minutes, so the total amount of minutes of combined play time for any team in a single game with no added time is 240 minutes. If the score is tied at the end of the 48 minutes, 5 minutes of extra time are played, this continues until a winner is decided.

Even though they can play multiple positions, players are usually classified according to the following positions:

- Guards
    - Point Guards
    - Shooting Guards
- Forwards
    - Small Forwards
    - Power Forwards
- Centers

We will mainly focus on the three main positions: Guards/Forwards/Centers.

You might be wondering: why basketball? The first reason is availability of data and the second one, because I love it.

The sport is played at a fast pace, with hundreds of plays in each single game, thousands of games in a season, and with a relatively small amount of on-court players, which gives them a lot of interactions with the ball, which in turn provides an oportunity to collect a great amount of data about each player performance.


## 📖 About 

- **Problem**: During the NBA's free agency period, when there are no games, players whose contracts have expired must negotiate a new contract with an existing team, which may be their last or a new one. In addition, players and teams can agree to a contract extension while the regular season is in progress, but only if certain conditions are met. In all these cases, both parties have to **negotiate the player's salary** and contract years, among other clauses, based on his performance. Therefore, this solution is useful for both sides of the contracts to estimate a baseline to start a negotiation.

- **Industries and applications**: Sports, NBA franchises, NBA Agents, NBA consultants, Basketball players.

- **Solution**: Building a dataset by connecting to the NBA API and performing various estimations and predictions with Machine Learning algorithms:
    - **Regression Models** to estimate players salaries.
    - **Binary classification** to predict All-NBA players selections.


You can see the whole project in the following **notebooks**:
 - [Building the dataset](https://github.com/agusle/nba-players-predictions/blob/main/nba-players-dataset.ipynb)
 - [Making estimations](https://github.com/agusle/nba-players-predictions/blob/main/nba_players_predictions.ipynb)

------------------

## ⚡️ Install and Run 

Listed below you'll find an example or application usage to run the project:

- **Open and execute in Google colab** (*you must be logged in with a google account*):
    - Open an internet browser and go to: https://colab.research.google.com/
    - On the menu select File / Open Notebook
    - Select the GitHub tab and copy the project url: https://github.com/agusle/nba-players-predictions
    - Click on *nba-players-dataset.ipynb* or *nba_players_predictions.ipynb* to see the notebook
    - Make a copy to your google drive acoount clicking the following icon ![copy-to-drive](https://github.com/agusle/nba-players-predictions/blob/main/img/copy-to-drive.PNG)
    - Go to tab *Runtime* and select *Run all*.

 
- **Open and execute in Jupyter notebook:**
    - Open an internet browser and got to: https://nbviewer.org/
    - Insert project path: https://github.com/agusle/nba-players-predictions and press Go! button.
    - Click on *nba-players-dataset.ipynb* or *nba_players_predictions.ipynb* to see the notebook
    - If you want to execute it click on *execute on binder* icon ![binder](https://github.com/agusle/nba-players-predictions/blob/main/img/binder.png)
    - Go to tab *Cell* and click on *Run all*.


- **Other ways** 
There are many other ways to open the notebook and run the whole project, you can see an example on the following link: https://soshnikov.com/education/how-to-execute-notebooks-from-github/

------------------

## 👍 Contribute
**Please follow these steps to get your work merged in.**

1. Add a [GitHub Star](https://github.com/agusle/nba-players-predictions) to the project.
2. Clone repo and create a new branch: `$ git checkout https://github.com/agusle/nba-players-predictions -b name_for_new_branch.`
3. Add a feature, fix a bug, or refactor some code :)
4. Write/update tests for the changes you made, if necessary.
5. Update `README.md`, if necessary.
4. Submit Pull Request with comprehensive description of changes