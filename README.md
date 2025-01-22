# INTRODUCTION

## Connect Four Rules 

Two players alternate dropping their colour of disc into a board (red or yellow). The objective of the game is to be the first player to get 4 discs in a row. The row can horizontal,vertical or diagonal but must be consecutive. The game is a draw if no win condition can be met by either play and the board is filled. 

## Aim

I am to build a AI that can effectively play the game and hopefully beat me! 

## 

# REQUIREMENTS

## Instillation

Pip install kaggle-environments 1.16.11 https://pypi.org/project/kaggle-environments/ 

```md
pip install kaggle-environments
```

## Summery 

### obs

obs.board : the game board
obs.mark : the piece assigned to the agent (1 or 2)

### config 

config.columns : number of columns in the game board (7)
config.rows: number of rows in the game board (6)
config.inarow : number of pieces a player needs to get in a row in order to win (4)



