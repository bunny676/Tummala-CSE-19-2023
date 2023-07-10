# Summary

| Date  | Notes
| :---- | :----
| 07/03 | Continued to work on implementing REINFORCE
| 07/04 | 4th of July so not much work done
| 07/05 | Continued to work on implementing REINFORCE (moved on from figuring out how grid data was stored)
| 07/06 | Continued to work on implementing REINFORCE
| 07/07 | Continued to work on implementing REINFORCE (basic code finished, onto bugfixing)

# Activities

In general, worked on implementing REINFORCE algorithm in gym-sokoban environment.

# Issues

gym-sokoban processes 8 outputs instead of 4 for ULDR movement and ULDR pushing boxes, which could potentially be an issue.
- Algorithm seems to work fine while ignoring this, might come up later however
Currently, the 3 rgb values are collapsed into 1 by just adding all of them equally. Will look into reducing space between pixels next week (create list that maps collapsed RGB values to counting numbers)
gym-sokoban requires rendering map multiple times to receive grid data

# Plans

Finish and mainly polish REINFORCE algorithm, test it + optimize, and move on to next algorithm.

# Article Summaries

None this week. So I should just remove this section.
