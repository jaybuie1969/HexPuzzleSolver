# HexPuzzleSolver
Python-based algorithm to find solution for the hexagonal puzzle in the pictures

As the pictures show, this Python script is all about an old puzzle.  A friend picked this up at Goodwill and gave it to me.  I have vague memories of my father having one on his dresser in the 1970s when I was a young boy, so I was intrigued.

Each of the seven haxagonal pieces can be placed on any of the seven post, with any rotation.  The goal is to get the pieces to line up so that the numbers are the same on each adjacent face.  See the third picture for the solved state.  It looks deceptively simple, but actually has over 1.4 billion board configurations, and only six are solutions -- all rotationally symetric to each other.

Updated Nobember 13, 2018 -- SWEET!
Modified the retational testing algorithm to quickly know when a given game peice ordering cannot produce a solution, and then bail out of that set of iterations - this cut the processing time on my machine from around 95 - 95 minutes to less than one second!
