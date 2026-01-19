---
title: "Sun L. vs Fruhvirtova L."
date: 2026-01-19
tournament: "Australian Open 2026"
surface: "Hard"
round: "R128"
totals_lean: "PASS"
totals_edge: 0.0
spread_lean: "PASS"
spread_edge: 0.0
confidence: "PASS"
---

# Sun L. vs Fruhvirtova L.

## Match & Event

| Field | Value |
|-------|-------|
| Tournament / Tier | Australian Open 2026 / Grand Slam |
| Round / Court / Time | R128 / TBD / TBD |
| Format | Best of 3, Standard tiebreaks |
| Surface / Pace | Hard / Medium-Fast |
| Conditions | Outdoor, Melbourne weather |

---

## Executive Summary

### CRITICAL DATA QUALITY ISSUE - RECOMMEND PASS

**Sun L. Statistics: INVALID**
- Scraper retrieved "Fajing Sun" (ATP #268, male player) instead of "Lulu Sun" (WTA player)
- All hold/break statistics are 0% due to tour mismatch (ATP query for WTA player)
- 0 matches in dataset - no reliable baseline for analysis
- Cannot generate valid game distribution model without correct player data

**Fruhvirtova L. Statistics: LIMITED**
- Only 6 matches in last 52 weeks (small sample size)
- Hold%: 71.2%, Break%: 37.5% (valid but limited data)
- Recent qualifier for AO main draw (3 wins in qualifying)

**Data Completeness: LOW**

### Totals

| Metric | Value |
|--------|-------|
| **Model Fair Line** | UNABLE TO CALCULATE |
| **Market Line** | O/U 21.5 |
| **Lean** | **PASS** |
| **Edge** | N/A - Insufficient Data |
| **Confidence** | **PASS** |
| **Stake** | 0 units |

### Game Spread

| Metric | Value |
|--------|-------|
| **Model Fair Line** | UNABLE TO CALCULATE |
| **Market Line** | Sun L. -1.5 games |
| **Lean** | **PASS** |
| **Edge** | N/A - Insufficient Data |
| **Confidence** | **PASS** |
| **Stake** | 0 units |

**Key Risks:**
- Sun L. data completely invalid (wrong player, wrong tour)
- Fruhvirtova L. limited sample size (only 6 matches)
- Cannot model expected games without valid hold/break statistics

**RECOMMENDATION: PASS ON BOTH TOTALS AND SPREAD**

---

## Data Quality Assessment

### Critical Issue: Tour Mismatch for Sun L.

**What Happened:**
1. Query for "Sun L." statistics on TennisAbstract
2. Scraper found "Fajing Sun" (ATP player, rank #268)
3. All statistics returned are for male ATP player
4. **Actual player:** Lulu Sun (WTA player)
5. **Result:** 0% hold, 0% break, 0 matches - completely invalid

**Why This Matters:**
- Hold% and Break% are PRIMARY inputs for totals/handicaps modeling
- Without valid hold/break statistics, cannot calculate:
  - Expected total games
  - Set score probabilities
  - Tiebreak likelihood
  - Expected game margin
- Game distribution model requires accurate service/return metrics

### Fruhvirtova L. Data Quality

**Sample Size:**
- Only 6 matches in last 52 weeks (tour-level)
- Small sample increases uncertainty in hold/break estimates
- Limited data for tiebreak frequency/win rate

**Available Statistics (Valid but Limited):**
- Hold%: 71.2%
- Break%: 37.5%
- Recent form: Just qualified for AO main draw (3-0 in qualifying)

**Limitations:**
- High variance due to small sample
- Qualifier data may not reflect main draw performance
- Insufficient match history for confident predictions

### Data Completeness Summary

| Component | Sun L. | Fruhvirtova L. | Status |
|-----------|--------|----------------|--------|
| Hold % | INVALID (0%) | Valid (71.2%) | INSUFFICIENT |
| Break % | INVALID (0%) | Valid (37.5%) | INSUFFICIENT |
| Matches in Dataset | 0 | 6 | INSUFFICIENT |
| Tiebreak Stats | INVALID | Limited | INSUFFICIENT |
| Game Distribution | INVALID | Limited | INSUFFICIENT |
| Overall Quality | **INVALID** | **LOW** | **PASS REQUIRED** |

---

## Sun L. - Data Profile (INVALID)

### Critical Warning

**ALL STATISTICS BELOW ARE FOR THE WRONG PLAYER (Fajing Sun, ATP)**

These statistics cannot be used for analysis of Lulu Sun (WTA player).

### Incorrect Data Retrieved

| Metric | Value (INVALID) | Issue |
|--------|-----------------|-------|
| **Player Retrieved** | Fajing Sun | Wrong player (male ATP) |
| **Ranking** | ATP #268 | Not WTA ranking |
| **Matches in Dataset** | 0 | No valid data |
| **Hold %** | 0% | Invalid (wrong tour) |
| **Break %** | 0% | Invalid (wrong tour) |
| **Avg Total Games** | N/A | No matches |
| **Tiebreak Data** | N/A | No matches |

### What Would Be Needed

To generate a valid analysis for **Lulu Sun (WTA)**, we would need:
1. Correct WTA player statistics from TennisAbstract
2. Hold% and Break% from last 52 weeks on hard courts
3. Minimum 15-20 matches for reliable estimates
4. Tiebreak frequency and win rate (minimum 10 TBs)
5. Recent form and game distribution data

**Current Status:** None of the above requirements met.

---

## Fruhvirtova L. - Data Profile (LIMITED)

### Rankings & Form

| Metric | Value | Note |
|--------|-------|------|
| **WTA Rank** | ~200s (qualifier) | Recently qualified for AO |
| **Recent Form** | 3-0 in AO qualifying | Limited main draw history |
| **Matches in Dataset** | 6 | Small sample size |

### Surface Performance (Hard - Last 52 Weeks)

| Metric | Value | Reliability |
|--------|-------|-------------|
| **Win %** | Unknown | Limited data |
| **Avg Total Games** | Unknown | Insufficient sample |
| **Breaks Per Match** | Derived from hold/break% | Small sample |

### Hold/Break Analysis (LIMITED SAMPLE)

| Category | Stat | Value | Sample Size Warning |
|----------|------|-------|-------------------|
| **Hold %** | Service Games Held | 71.2% | Only 6 matches |
| **Break %** | Return Games Won | 37.5% | Only 6 matches |

| **Tiebreak** | TB Frequency | Unknown | Insufficient data |
| | TB Win Rate | Unknown | Insufficient data |

**Sample Size Warning:**
- 71.2% hold from 6 matches = high uncertainty (±10% CI likely)
- 37.5% break from 6 matches = high uncertainty (±10% CI likely)
- Typical confidence requires 15-20+ matches

### Recent Context

**Australian Open Qualifying (2026):**
- Won 3 qualifying matches to reach main draw
- Performance in qualifiers may not translate to main draw
- Facing higher-quality opposition in R128

---

## Analysis Limitations

### Why We Cannot Generate Valid Recommendations

**1. No Valid Data for Sun L.**
- Cannot calculate expected hold % (input: 0%, invalid)
- Cannot calculate expected break % (input: 0%, invalid)
- Cannot model set score probabilities
- Cannot estimate total games distribution
- Cannot calculate game margin

**2. Insufficient Data for Fruhvirtova L.**
- Only 6 matches in sample
- Hold/break estimates have wide confidence intervals (±10%)
- Unknown tiebreak tendencies
- Limited understanding of game distribution

**3. Cannot Model Game Distribution**
Without valid hold/break for both players:
- P(6-0, 6-1, 6-2, 6-3, 6-4, 7-5, 7-6) = Unknown
- P(Straight Sets) = Unknown
- P(At Least 1 TB) = Unknown
- E[Total Games] = Cannot calculate
- E[Game Margin] = Cannot calculate

**4. Cannot Compare to Market**
- Market Line: O/U 21.5 games
- Model Line: **UNABLE TO CALCULATE**
- Edge: **CANNOT DETERMINE**

---

## Market Lines (For Reference Only)

### Totals Market

| Source | Line | Over Odds | Under Odds |
|--------|------|-----------|------------|
| Sportsbet.io | O/U 21.5 | 1.85 | 1.91 |

**No-Vig Implied Probabilities:**
- P(Over 21.5) ≈ 52.3%
- P(Under 21.5) ≈ 47.7%

**Cannot Compare:** No valid model to assess edge.

### Game Spread Market

| Source | Line | Favorite Odds | Underdog Odds |
|--------|------|---------------|---------------|
| Sportsbet.io | Sun L. -1.5 | 1.80 | 1.96 |

**No-Vig Implied Probabilities:**
- P(Sun L. covers -1.5) ≈ 54.3%
- P(Fruhvirtova L. covers +1.5) ≈ 45.7%

**Cannot Compare:** No valid model to assess edge.

---

## Partial Analysis (Educational Purposes Only)

### What We Could Say with Fruhvirtova L. Data Alone

**If we had valid Sun L. data**, here's how Fruhvirtova L.'s limited statistics would inform the analysis:

**Fruhvirtova L. Hold% = 71.2%**
- Below tour average (~75-80% for WTA)
- Suggests vulnerability on serve
- Would expect opponent to generate breaks

**Fruhvirtova L. Break% = 37.5%**
- Solid return game (tour average ~25-30%)
- Can generate break opportunities
- Would compete on return games

**Expected Game Patterns (Hypothetical):**
- Lower hold% (71.2%) suggests:
  - More breaks in match (higher total games likely)
  - Competitive sets (6-4, 7-5 more common than 6-2, 6-3)
  - Moderate tiebreak probability (not extremely high)

**But:**
- Sample size too small to have confidence (only 6 matches)
- No data for opponent (Sun L. data invalid)
- Cannot complete the analysis

---

## What Would Be Needed for Valid Analysis

### For Sun L. (Currently Missing)

**Critical Requirements:**
1. **Correct Player Data:** Lulu Sun (WTA) statistics
2. **Hold %:** Service games held (hard court, last 52 weeks)
3. **Break %:** Return games won (hard court, last 52 weeks)
4. **Minimum Sample:** 15-20 matches minimum
5. **Tiebreak Stats:** Frequency and win rate (10+ TBs preferred)
6. **Game Distribution:** Average total games, straight sets %
7. **Recent Form:** Last 10 match record, dominance ratio

### For Fruhvirtova L. (Currently Insufficient)

**Improvement Needs:**
1. **Larger Sample:** Need 15-20+ matches (currently only 6)
2. **Surface-Specific:** More hard court matches in dataset
3. **Tiebreak Data:** Currently unknown, need 10+ TBs
4. **Game Distribution:** Average total games, set patterns
5. **Form Context:** Main draw performance (not just qualifiers)

### For Valid Modeling

With correct data for both players, we could calculate:
- Set score probabilities: P(6-0) through P(7-6)
- Expected total games with 95% CI (e.g., 22.3 ± 3 games)
- Expected game margin with 95% CI (e.g., -2.1 ± 4 games)
- P(Over 21.5) and compare to market implied 52.3%
- Edge calculation for totals and spread
- Confidence assessment (HIGH/MEDIUM/LOW)

**Current Status:** None of the above possible with invalid Sun L. data.

---

## Recommendations

### Totals Recommendation

| Field | Value |
|-------|-------|
| **Market** | Total Games |
| **Selection** | **PASS** |
| **Target Price** | N/A |
| **Edge** | Cannot Calculate |
| **Confidence** | **PASS** |
| **Stake** | 0 units |

**Rationale:**

Cannot generate a valid totals model without accurate hold/break statistics for both players. Sun L. data is completely invalid (wrong player, wrong tour), and Fruhvirtova L. has only 6 matches in the dataset. Expected total games requires:
1. Valid hold% for both players
2. Valid break% for both players
3. Tiebreak probability modeling
4. Set score distribution

None of these can be calculated with current data quality. **PASS is the only responsible recommendation.**

### Game Spread Recommendation

| Field | Value |
|-------|-------|
| **Market** | Game Handicap |
| **Selection** | **PASS** |
| **Target Price** | N/A |
| **Edge** | Cannot Calculate |
| **Confidence** | **PASS** |
| **Stake** | 0 units |

**Rationale:**

Cannot generate a valid game margin model without accurate hold/break statistics for both players. Expected game margin calculation requires:
1. Hold/break differential between players
2. Straight sets probability
3. Set win probabilities
4. Game distribution modeling

With Sun L. data invalid and Fruhvirtova L. limited to 6 matches, confidence intervals would be excessively wide (±8+ games likely). **PASS is required.**

### Pass Conditions

**Current Situation Meets Multiple Pass Criteria:**
- ✓ Hold/break data missing for Sun L. (completely invalid)
- ✓ Insufficient sample size for Fruhvirtova L. (only 6 matches)
- ✓ Cannot calculate model edge (no valid expected games/margin)
- ✓ Data quality: LOW (fails minimum threshold)
- ✓ Uncertainty too high for any confidence level

**When This Match Becomes Bettable:**
- After collecting correct WTA statistics for Lulu Sun
- After verifying minimum 15-20 match sample for both players
- After confirming tiebreak statistics available
- After generating valid game distribution model
- After calculating edge ≥ 2.5% on totals or spread

**Until Then:** **PASS on both totals and spread markets.**

---

## Risk & Unknowns

### Variance Drivers (If Data Were Valid)

**Theoretical Considerations:**
- **Tiebreak Volatility:** Unknown tiebreak tendencies for both players
- **Hold Rate Uncertainty:** Sun L. invalid, Fruhvirtova L. ±10% CI likely
- **Straight Sets Risk:** Cannot assess without valid model
- **Qualifier Variable:** Fruhvirtova coming from qualifiers (performance variance)

### Data Limitations (Critical)

**Sun L.:**
- ✗ All statistics invalid (wrong player retrieved)
- ✗ 0 matches in dataset
- ✗ ATP data used for WTA player
- ✗ Cannot be used for any analysis

**Fruhvirtova L.:**
- ⚠️ Only 6 matches in dataset (need 15-20+)
- ⚠️ Tiebreak data unavailable
- ⚠️ Limited game distribution history
- ⚠️ Recent qualifier performance may not translate

**Model:**
- ✗ Cannot calculate expected games (missing valid inputs)
- ✗ Cannot calculate expected margin (missing valid inputs)
- ✗ Cannot generate confidence intervals
- ✗ Cannot assess edge

### Correlation Notes

**N/A** - No positions recommended due to insufficient data.

---

## Sources

1. **TennisAbstract.com** - Attempted data collection (Last 52 Weeks)
   - **Sun L. ISSUE:** Retrieved wrong player (Fajing Sun, ATP instead of Lulu Sun, WTA)
   - **Fruhvirtova L.:** Limited data retrieved (6 matches only)
   - Data quality: LOW - insufficient for analysis

2. **Sportsbet.io** - Match odds
   - Totals: O/U 21.5 (Over 1.85, Under 1.91)
   - Spread: Sun L. -1.5 (1.80 vs 1.96)
   - Market lines available but cannot be compared to model

3. **Market Context:**
   - Market implies Sun L. slight favorite (-1.5 games)
   - Market implies moderate total (21.5 games)
   - Without valid model, cannot assess if market is efficient or inefficient

---

## Verification Checklist

### Core Statistics
- [ ] ✗ Hold % collected for both players (Sun L. INVALID, Fruhvirtova L. limited)
- [ ] ✗ Break % collected for both players (Sun L. INVALID, Fruhvirtova L. limited)
- [ ] ✗ Tiebreak statistics collected with adequate sample size (both insufficient)
- [ ] ✗ Game distribution modeled (cannot model without valid inputs)
- [ ] ✗ Expected total games calculated with 95% CI (cannot calculate)
- [ ] ✗ Expected game margin calculated with 95% CI (cannot calculate)
- [ ] ✗ Totals line compared to market (no valid model)
- [ ] ✗ Spread line compared to market (no valid model)
- [ ] ✗ Edge ≥ 2.5% for any recommendations (N/A - PASS recommended)
- [ ] ✓ **NO moneyline analysis included**

### Enhanced Analysis
- [ ] ✗ Elo ratings extracted (not available/reliable for both players)
- [ ] ✗ Recent form data included (Sun L. invalid, Fruhvirtova L. limited)
- [ ] ✗ Clutch stats analyzed (insufficient data)
- [ ] ✗ Key games metrics reviewed (insufficient data)
- [ ] ✗ Playing style assessed (insufficient data)

### Data Quality Assessment
- [x] ✓ Data quality issue identified and documented
- [x] ✓ Sun L. tour mismatch explained (ATP vs WTA)
- [x] ✓ Fruhvirtova L. sample size limitation noted (6 matches)
- [x] ✓ PASS recommendation justified due to data quality
- [x] ✓ Requirements for valid analysis documented

### Report Quality
- [x] ✓ Data quality warnings prominently displayed
- [x] ✓ Clear explanation of why analysis cannot proceed
- [x] ✓ Educational partial analysis provided (Fruhvirtova data context)
- [x] ✓ Specific requirements for valid analysis documented
- [x] ✓ Responsible PASS recommendation made for both markets

---

## Summary

**PASS ON BOTH TOTALS (O/U 21.5) AND SPREAD (Sun L. -1.5)**

**Primary Reason:** Critical data quality failure - Sun L. statistics are completely invalid due to tour mismatch (ATP player retrieved instead of WTA player). Combined with Fruhvirtova L.'s limited sample size (only 6 matches), there is insufficient data to generate a valid game distribution model.

**What's Missing:**
1. Correct WTA statistics for Lulu Sun (currently showing Fajing Sun, ATP)
2. Larger sample size for Fruhvirtova L. (need 15-20+ matches, currently 6)
3. Tiebreak statistics for both players
4. Game distribution data for both players

**Responsible Action:** PASS until correct data can be collected and validated.

**Edge:** Cannot calculate (insufficient valid data)
**Confidence:** PASS (data quality below minimum threshold)
**Stake:** 0 units on both totals and spread
