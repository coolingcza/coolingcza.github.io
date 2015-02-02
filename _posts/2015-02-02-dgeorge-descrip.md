---
title: Description for Derek's RPS Program
---

There were a number of things that I liked about Derek's program but two stood out.

First was that the player's moves were chosen automatically by sampling the moves array:

```ruby
    x = moves.sample
    y = moves.sample
```

The second was that rather than playing all of the rounds that the user indicated, the game is
stopped as soon as one player's score hits the majority of the number of rounds:

```ruby
until player1.score == "#{best_of}".to_f.ceil || player2.score == "#{best_of}".to_f.ceil do
```