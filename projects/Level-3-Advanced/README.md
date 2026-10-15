# Level 3 (Advanced) — Cricket Fielding Analysis

## Objective
Analyze the fielding performance of 3 players from IPL 2024 Final (KKR vs SRH) using a custom Performance Score (PS) formula.

## Match Details
- **Match:** IPL 2024 Final
- **Teams:** KKR vs SRH
- **Innings Analyzed:** 1st (SRH batting)
- **Fielding Team:** Kolkata Knight Riders
- **Venue:** MA Chidambaram Stadium, Chennai

## Players Analyzed
1. **Mitchell Starc** — 2 catches, 1 dropped catch
2. **Rahmanullah Gurbaz** (WK) — 3 catches
3. **Ramandeep Singh** — 1 catch

## Performance Score Formula
 PS = (CP×1) + (GT×1) + (C×3) − (DC×3) + (ST×3) + (RO×3) − (MRO×2) + (DH×2) + RS

## Results

| Player | Catches | Drops | Runs Saved | PS |
|--------|---------|-------|------------|-----|
| Mitchell Starc | 2 | 1 | 0 | 3 |
| Rahmanullah Gurbaz | 3 | 0 | 3 | 12 |
| Ramandeep Singh | 1 | 0 | 1 | 4 |

**Top Performer:** Rahmanullah Gurbaz (PS = 12)

**Top Performer:** Rahmanullah Gurbaz (PS = 12)

## Files
- `cricket_fielding_analysis.csv` — Ball-by-ball fielding events
- `performance_score.csv` — Calculated scores

## Key Insights
- Gurbaz's 3 catches as wicketkeeper made him the highest scorer.
- Starc's 2 catches were offset by 1 dropped catch.
- Ramandeep's spectacular catch showed high fielding quality.

## Personal Observation

While recording the fielding data, I noticed that wicketkeepers 
tend to accumulate higher PS scores due to the frequency of catches 
behind the stumps. Gurbaz's 3 catches highlighted this — a 
wicketkeeper's contribution is often underrated in fielding analysis.

I also noticed Starc's dropped catch (Pat Cummins at long-on) 
could have been a turning point in a low-scoring final. This 
shows how individual fielding moments can shift match momentum.

## References
- Task PDF: ShadowFox Data Science Internship
- Match data: IPL 2024 Final (KKR vs SRH)