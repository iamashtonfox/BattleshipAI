#### This is an AI I designed based on a Bayesian network to be able to play Battleship.

<img width="1381" alt="Screenshot 2024-05-22 at 6 21 42 PM" src="https://github.com/iamashtonfox/BattleshipAI/assets/140920863/e7f0cff6-cbc1-4d13-9a05-56677d46417e">



# TO RUN THE AI:

#### 1) Copy the repo and cd into {wherever}/BattleshipAI

## ON MAC/LINUX:
#### 2) In a terminal at the top-level of the file, run: "javac -cp "./lib/*:." @battleship.srcs" to compile
#### 3) Run "java -cp "./lib/*:." edu.bu.battleship.Main --p1Agent src.pas.battleship.agents.ProbabilisticAgent"

## ON WINDOWS/:
#### 2) In a terminal at the top-level of the file, run: "javac -cp "./lib/*;." @battleship.srcs" to compile
#### 3) Run "java -cp "./lib/*;." edu.bu.battleship.Main -q src.pas.battleship.agents.TetrisQAgent"

## After compiling, you can also run "java -cp "./lib/*:." edu.bu.battleship.Main -h" to return a list of usable command-line flags for running the AI as well as a description of what they do.

# Follows normal Battleship rules. The --p1Agent flag designates the AI as attacking Player2 on the right-hand side. Player2 attacks Player1 on the left-hand side randomly.
