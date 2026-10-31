# Results and Discussion

## What I studied

I compared match results for six men's singles badminton players during 2024 and 2025. The dataset contains **454 separate matches** involving at least one of them. For player-by-player comparisons, those matches become **488 player-match records** because a match between two selected players is counted once for each player's record.

For questions about individual games, I used only the **475 player-match records** with complete and consistent scores.

## Main findings

### Overall win rates

**SHI Yu Qi had the highest win rate in the selected data: 82 wins from 95 matches, or 86.3%.** Viktor AXELSEN followed with 78.7% (48/61), and Kunlavut VITIDSARN had 74.1% (80/108).

These numbers describe the matches in the dataset. They do not prove which player is the strongest because their opponents and schedules were different.

### Comparing the two years

SHI Yu Qi's win rate increased from **83.7% in 2024 (41/49)** to **89.1% in 2025 (41/46)**. LEE Zii Jia showed the largest decrease: **69.4% (34/49)** in 2024 compared with **28.6% (2/7)** in 2025, a difference of **40.8 percentage points**.

LEE Zii Jia's result is the one I would be most careful about interpreting. His 2025 percentage comes from only seven matches, so it could change a lot with just a few more results. It would be misleading to treat the drop as a precise measure of how much his ability changed.

### After winning the first game

Players in the selected sample who won Game 1 went on to win the match **282 out of 315 times (89.5%)**, using only completed match scores.

This makes sense because badminton matches are won by taking two games. I see this as a useful conditional percentage, not proof that the first game alone determines the final result.

### Matches that reached a third game

Across the six selected players, **120 of 178 player-match records (67.4%)** from completed three-game matches were wins. The records are counted from each selected player's perspective, so 178 does not mean 178 separate matches.

These results are useful for comparing this particular sample of longer matches, but there is not enough information here to measure a player's mental toughness or ability to handle pressure.

## What the results mean

The most useful part of this project was seeing how much a percentage depends on the number of matches behind it. A result based on seven matches should not be interpreted with the same confidence as one based on fifty or ninety matches.

I also learned that statistics alone do not explain every reason for a result. Opponent strength, injuries, tournament schedules, and missing records can change what a comparison means, even when the calculations are correct.

## Limitations

- The project includes only six chosen players and two calendar years.
- Each player faced a different mix of opponents; I did not adjust for opponent rankings.
- Match data came from a public third-party collection, not a dataset independently checked against every official result.
- Records without complete scores were excluded from first-game and three-game calculations.
- Matches are not necessarily independent observations, so percentages and the notebook's Wilson intervals should be read cautiously.
- The analysis describes recorded results; it cannot establish cause and effect or predict future performance.

## Conclusion

This project helped connect my interest in badminton with the basic statistical ideas I have been learning. Python made it possible to work with more matches than I could reasonably compare by hand. The biggest takeaway is simple: **a percentage is more useful when you also know the sample size and what the data leaves out.**

## Data source

Sahil Motyar, [bwf-match-data](https://github.com/SahilMotyar/bwf-match-data).
