# Obstacle Removal

School project : removing obstacles in front of a background.

We have at our disposal several pictures of a background with various obstacles hiding parts of it, and we want to extract the entire background using a "meaningful clique" algorithm.

We use three different techniques : 
  - First an algortihm computing a vector median
  - Then the more advanced "clique algorithm"
  - Finally the previous "clique algorithm" with a few tweaks : notably the use of spatial patches on the image
