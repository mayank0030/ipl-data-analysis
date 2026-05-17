# IPL Crunch '26 — Data Analytics Challenge

An end-to-end data analytics project analyzing **1,226 IPL matches** (2007–2026) with **291,574 ball-by-ball records** from Cricsheet.

Built with Python, Pandas, Matplotlib, and Seaborn. Submitted for the Wooble IPL Crunch '26 challenge.

---

## Key Questions Answered

### 1. Do teams that win the toss actually win more matches?

**No.** The toss winner wins only **50.6%** of matches — essentially a coin flip.

- Teams that **field first** win **53.8%** of the time (66% of captains choose to field)
- Teams that **bat first** win only **44.3%** of the time
- The toss advantage is minimal in IPL. Skill and execution matter far more.

### 2. Which phase impacts victory the most?

Phase | Winning RR | Losing RR | Gap
---|---|---|---
Powerplay (1–6) | 8.51 | 7.60 | +0.91
Middle (7–15) | 8.23 | 7.24 | +0.99
**Death (16–20)** | **10.88** | **8.90** | **+1.98**

**Death overs** show the biggest gap between winners and losers. Teams that finish strong win.

### 3. Top Batters Across Seasons

| Player | Runs |
|---|---|
| **V Kohli** | 9,155 |
| RG Sharma | 7,291 |
| S Dhawan | 6,769 |

### 4. Top Bowlers Across Seasons

| Player | Wickets |
|---|---|
| **YS Chahal** | 229 |
| B Kumar | 221 |
| SP Narine | 205 |

### 5. Hidden Patterns

- **Chasing advantage:** Teams batting second win **53.9%** of matches
- **Run rate evolution:** IPL average run rate has climbed from **7.98** (early seasons) to **9.30** (recent) — a **16.5%** increase
- **60 unique venues** have hosted IPL matches
- Teams overwhelmingly prefer to **field first** (66% of decisions), and it pays off

---

## Files

| File | Description |
|---|---|
| `ipl_crunch_26_analysis.ipynb` | Main Jupyter notebook with all code, analysis, and charts |
| `matches.csv` | Consolidated match-level data (1,226 rows) |
| `deliveries.csv` | Consolidated ball-by-ball data (291,574 rows) |
| `01_toss_vs_win.png` | Toss advantage analysis charts |
| `02_phase_impact.png` | Phase-wise run rate comparison |
| `03_top_batters.png` | Top run-scorers across IPL history |
| `03b_top_batter_per_season.png` | Highest run-scorer each season |
| `04_top_bowlers.png` | Top wicket-takers across IPL history |
| `04b_top_bowler_per_season.png` | Highest wicket-taker each season |
| `05_hidden_patterns.png` | Chasing advantage, venue impact |
| `06_run_rate_trend.png` | IPL run rate evolution over time |

---

## Tools Used

- **Python 3** — Pandas, NumPy, Matplotlib, Seaborn
- **Google Colab** — Runtime environment
- **Cricsheet** — Raw IPL data source

---

## How to Run

1. Open `ipl_crunch_26_analysis.ipynb` in Google Colab or Jupyter
2. Upload `matches.csv` and `deliveries.csv` when prompted
3. Run all cells (Runtime → Run all)
4. Download the results ZIP with all charts

---

## Key Insight

> *[Add your one surprising insight here — something you discovered in the data that you didn't expect.]*

---

**Author:** [Your Name]  
**Challenge:** IPL Crunch '26 by Wooble  
**Dataset:** Cricsheet (https://cricsheet.org)
