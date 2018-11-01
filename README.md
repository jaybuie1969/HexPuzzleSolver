# HexPuzzleSolver

As the pictures show, this Python script is all about an old puzzle.  A friend picked this up at Goodwill and gave it to me.  I have vague memories of my father having one on his dresser in the 1970s when I was a young boy, so I was intrigued.

Each of the seven haxagonal pieces can be placed on any of the seven post, with any rotation.  The goal is to get the pieces to line up so that the numbers are the same on each adjacent face.  See the third picture for the solved state.  It looks deceptively simple, but actually has over 1.4 billion board configurations, and only six are solutions -- all rotationally symetric to each other.

This script is a sequential brute-force solution to this puzzle.  It works and is a good first effort, but it trades computing power for time.  The next version will be threaded so that it can be parallelized and make effective use of an on-demand cloud environment like AWS or Azure.
