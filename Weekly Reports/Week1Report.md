# Summary

| Date  | Notes
| :---- | :----
| 06/26 | Researched environments to use
| 06/27 | Investigated multiple environments, settled on sokoban
| 06/28 | Worked on installing sokoban environment, played around with torch
| 06/29 | Finished setting up sokoban environment, got basic random movement program running
| 06/30 | Found some bugs in how implementation was working so fixed them, began implementation of REINFORCE

# Activities

Set up gym-sokoban environment
Created basic torch neural network to simulate architecture of end network
   - 100 inputs for a 10 by 10 grid, 4 outputs for ULDR
Began implementation of reinforce by further researching functions used in gym-sokoban

# Issues

gym-sokoban runs on the gym environment instead of the gymnasium environment, so it requires a different package to be imported and slightly different syntax.
Many bugs appeared in the process of installing and implementing the base gym-sokoban code, like the aforementioned gym/gymnasium difference and the lack of functionality on Google Colab that required a switch to running code on my local machine.

# Plans

Main (and really only) plan is to continue to work on the REINFORCE algorithm implementation.
- start setting up the deep learning pipeline, and
- start working with the Nano and cameras.
