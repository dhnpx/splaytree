# splaytree
This is a refactor to have the animation run a set number of times. 

- The insert box was changed to the number of nodes to insert with a random number up to 999. 
- There is a bit of jank with the step/skip back. It only works until the last node inserted. Then it just skips through the queued nodes
  until one by one until none are left. Then it continues to undo the last nodes/steps.

This was from 
https://www.cs.usfca.edu/~galles/visualization/SplayTree.html

