# Summary

| Date  | Notes
| :---- | :----
| 07/17 | Began to rewrite some of the functions of the Sokoban env to speed up my code and hopefully make it perform better (stop running into walls)
| 07/18 | Continued modifying environment and my code to have better accuracy
| 07/19 | Developed new model to make Sokoban actually train
| 07/20 | Made a few more edits to the Sokoban env to make it run faster and give better rewards
| 07/21 | Returned to working with a2c

# Activities

I modified the environment I was using to better suit my project (made rewards multiplicative instead of additive, added rewards for pushing box and penalty for trying to make an invalid move, changed how reset and step were handled to fix crash problems and optimize code)

# Issues

Throughout the week, my network was consistently performing awful even after several thousand iterations. However, through all the changes I made with the reward system calculations and upgrading the network, I was able to get a player that, while still performing somewhat terribly, is able to play like a human.

# Plans

Continue to look at a2c, return to exploring forward-backward reinforce

# Article Summaries

Didn't really read any articles this week.
