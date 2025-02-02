## Stone paper scissors

The game Rock-Paper-Scissors is a simple hand game played between two players. Each player simultaneously chooses one of three moves: Rock (which crushes Scissors), Paper (which covers Rock), or Scissors (which cuts Paper). The winner is determined based on these interactions, with ties occurring when both players select the same move. Let's implement it!

You will need to have a class named `StonePaperScissors`. For playing the game, the user needs to use the class like this:

```st
game := StonePaperScissors new.
result := game play: #paper against: #stone.
result "#stone"
```

![Stone paper scissors.](./figures/StonePaperScissorsGame2.pdf)