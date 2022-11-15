# Chess-2
Chess 2 by Oats Jenkins

Install: Download Chess2.html and run it in your browser of choice.

Based on Oats Jenkins youtube video "I made a BETTER chess":
https://www.youtube.com/watch?v=mcivL8u176Y

Thanks to Oats Jenkins for the rules and assets
Thanks to Chess.com for sound effects (I don't know if I'm allowed to use these)

My programming is a bit dodgy and the graphics could definitely be cleaned up

Let me know if you find any bugs, there probably are a few

6/28/22: Fixed a bug where the monkey could capture an enemy piece on the same turn as he rescues the king (which I assume is not allowed)

Ambiguous rules:
Can the monkey jump back to the same square it started on and end the turn there? In this ruleset he cannot

Can the monkey or king capture a piece when landing after a rescue? In this ruleset they cannot

Bugs: Funky behavior with dragging vs clicking that I want to fix (emulate chess.com)

Inefficiencies: The code could be greatly compacted if I used general methods instead of specific if-else cases
