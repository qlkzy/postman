# Message list

## Player emitted
* `%s` to tell Postman your AI's name, needs to be output before/on-receipt-of an `ident %d %d %d` message
* `play %s` plays a character card %s from your hand
* `forfeit` honourable way of admitting your game is over

## Postman emitted
* `reveal %d %s` tells you the player %d hand card character name %s
* `out %d (%s (%s))` tells you player %d is out and the zero, one or two characters their hand contained %s and %s
* `ident %d %d %d` tells you your player id, the id of first player and the number of players (*ACTION REQUIRED*)
* `begin` tells you the initial hands have been dealt and play is commencing
* `player %d` tells you the turn of player %d is commencing
* `draw %s` tells you that you just drew %s character card
* `played %d %s (%d (%s))` tells you the player ID, the character the player played, possibly the target player and then possibly the target character
* `protected %d` tells you the player %d cannot be acted upon because they have played a Priestess
* `swap %s` tells you to swap your card for character %s (*ACTION REQUIRED*)
* `discard %d %s` tells you player %d just discarded card character %s (*ACTION REQUIRED*)
