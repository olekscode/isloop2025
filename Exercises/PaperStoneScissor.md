## Rock paper scissors

The game Rock-Paper-Scissors is a simple hand game played between two players. Each player simultaneously chooses one of three moves: Rock (which crushes Scissors), Paper (which covers Rock), or Scissors (which cuts Paper). The winner is determined based on these interactions, with ties occurring when both players select the same move. Let's implement it!

You will need to have a class named `RockPaperScissors`. For playing the game, the user needs to use the class like this:

```st
game := RockPaperScissors new.
result := game play: #paper against: #rock.
result "#paper"
```

![Rock paper scissors.](StonePaperScissorsGame2.pdf)
